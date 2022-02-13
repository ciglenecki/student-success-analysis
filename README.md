# Student success analysis

[report.pdf](./report.pdf) is the final product

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

KS - if P = 1 that means that data surley come from same distribution. If P = 0 then data comes from different distributions

# 📋 Todo:
- [ ] spellcheck
- [ ] write introduction to the problem

# Contributors


<table>
  <tr>
    <td align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Blank_square.svg/2048px-Blank_square.svg.png" width="100px;" alt=""/><br /><sub><b>Magda Radić</b></sub><br /></td>
    <td align="center"><a href="https://github.com/tprhat"><img src="https://avatars.githubusercontent.com/u/33128908?v=4" width="100px;" alt=""/><br /><sub><b>Tomislav Prhat</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/matejciglenecki"><img src="https://avatars.githubusercontent.com/u/12819849?v=4" width="100px;" alt=""/><br /><sub><b>Matej Ciglenečki</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/pdragojevic"><img src="https://avatars.githubusercontent.com/u/76600733" width="100px;" alt=""/><br /><sub><b>Petar Dragojević</b></sub></a><br /></td>

</table>