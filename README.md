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
- [ ] Question (Tomislav): Are students more successful in maths or the main subject?
- [ ] Question (Matej): Which schools perform better than other schools in which subjects?
  - [ ] Create a "matrix" of schools/subjects
  - [ ] Later, you can sort for a specific subject, e.g. "Math" and check top 5 schools
- [ ] Question (Magda): Which variable is the best predictor of success on a specific subject
  - [ ] Later, create add top predicting variables for all subjects
- [ ] Question (Petar): How does student's time put into studying result in the final grade? 
