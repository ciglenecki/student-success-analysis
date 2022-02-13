# Student success analysis - 19.01.2022

**❗Tidyverse is core package for wrangling, filtering, visualizing and processing data. ❗**

# 📁 Directory structure

### src
All files related to R including the dataset

### pdfs
Descriptions and guides for the project

### cheatsheets
Tidyverse cheat sheets in pdf format

### auditorne
helpful reference to already existing problems and their solutions

# ⚙️ Setup notes
## ⬇️ Installation
Installation links:

- https://www.rstudio.com/products/rstudio/download/
- https://cran.r-project.org/bin/windows/base/

Linux - R installation (tidyverse requires these dependencies):
- ``` 
  sudo apt-get install r-cran-curl r-cran-openssl r-cran-xml2 libxml2-dev
  ```
## 📦 R packets
1. Open RStudio -> Open Project -> student-success-analysis **.Rproj**
2. File called student-success-analysis **.Rmd** should open up, 
    - if it didn't open: navigate to it using the bottom right panel "Files" and double click the file
3. Run the first chunk in the file (Ctrl + Shift + Enter) which contains `library` function
4. Popup will open asking you to install the packets, press yes. This took me **20 minutes**

# Notes:
## Rmd
hiding chunks https://bookdown.org/yihui/rmarkdown-cookbook/hide-one.html

KS - if P = 1 that means that data surley come from same distribution
if P = 0 then data comes from different distributions

# 📋 Todo:

- [x] Loading the dataset
- [x] Describing the dataset
- [ ] Handling missing values
- [ ] Transforming nominal columns to nominal
- [ ] Transforming binary columns to binary (?)
- [ ] Filter missing values
- [ ] 
- [ ] 
- [ ] ... add todos here ...
- [ ]
- [ ] 
- [ ] 
- [ ] 
- [ ] 
- [ ] Question (Matej): Does transport affect success
- [ ] Question (Tomislav): Are students more successful in maths or the main subject?
- [ ] Question (Matej): Which schools perform better than other schools in which subjects?
  - [ ] Create a "matrix" of schools/subjects
  - [ ] Later, you can sort for a specific subject, e.g. "Math" and check top 5 schools
  - [ ] T test - pair
  - [ ] KS test liliforce za normalizacijski test
    - check for how many values is liliforce consistent. If your you have enough values use the test. If not, assume non-normality on data
    - možemo ubaciti testove ali i dalje gledamo podatke kao ne-normalne 
      - mozda izbaciti F test jer on nije robustan na nenormalne podatke
    - pa zbog toga korsititi T test gdje su varijance nejednake


- [ ] Question (Magda): Which variable is the best predictor of success on a specific subject
  - [ ] Later, create add top predicting variables for all subjects
- [ ] Question (Petar): How does student's time put into studying result in the final grade? 



# Notes 20.01

Predviđanje uspjeha - koje varijable najvise utjecu

- G3_mat - uspjeh za mat
- R^2 - koliko varijance u izlaznoj varijabli (G3_mat) objasnjava neka varijabla

R^2 - veća vrijednost - to je bolji model, tj. više objašnjava vrijednosti (varijance)

Pogledati detaljno R^2

p-vrijednost u ovom kontesktu:
- usporeduju se modeli medusobono na nacin da se izostavlja jedna varijabla
- što je p niži to varijabla ima veći utjecaj
- p - vjerojatnost da je ta varijabla nesignifikantna

Multiple R-squared se povecava dodajemo nebitne varijable 

Pretpostavka - reziduali moraju biti normalni
- u nasem slucaju nisu 


ANOVA
- uzorci moraju biti izvuceni iz normalne distribucuje
- moraju li svi podaci proizlaziti iz normalne distribucije (?)

lm(students$G_total ~ students$traveltime)

- regresor je students$traveltime (provjeriti jel to u redu naziv)
- pogledati naziv za (students$G_total)


model = lm(students$G_total ~ students$traveltime)

summary(model)

traveltime."15 - 30 min"
traveltime."> 30 min"


Detaljnije pogledati KS vs Lillie


Pogledati kako K-squared Bartlett odjeđuje p

Naučiti ANOVU (i ostalo)

Provjeritit zasto su reziduali "neagtivni" (jesu li rezudiali uopce)
