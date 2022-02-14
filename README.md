# Student success analysis


[report.pdf](./report.pdf) is the final product

## Assignment

**Grade: 38/40**

The main goal of the project was to create a report. The report had to contain clearly explained concepts of statistical data analysis applied to the existing dataset. There weren't restrictions for the selection of statistical methods, as long as they were applied to the appropriate context and covered in the course's curriculum. The report consists of the test cases selected from the recommended list of test cases provided by faculty personnel or cases made up by team members. One of the requirements was that the R language had to be used to analyze the data and generate the report.

The project's grade depended on the quality of the report and oral examination done by faculty personnel which examined the knowledge of the theory of the methods used (why you may or may not use a particular test, assumptions for tests used, details of the statistical methods, etc.).


### Dataset

The dataset includes answers to survey questions with grades in mathematics and Portuguese of two students high schools. Collecting data on student achievement in teaching is a prerequisite for analyzing and improving the quality of education system. Details of the dataset are located at [pdfs/dataset_documentation.pdf](./pdfs/dataset_documentation.pdf) 


## 📁 Directory structure

| Directory                     | Description                                                        |
| ----------------------------- | ------------------------------------------------------------------ |
| [auditorne](./auditorne/)     | helpful reference to already existing problems and their solutions |
| [cheatsheets](./cheatsheets/) | tidyverse cheat sheets in pdf format                               |
| [pdfs](./pdfs/)               | dataset and project descriptions                                   |
| [src](./src/)                 | Rmd source files and dataset                                       |



## ⬇️ Installation
### Windows
- Rstudio - https://www.rstudio.com/products/rstudio/download/#download
- R - https://cran.r-project.org/bin/windows/base/

### Linux
- Rstudio - https://www.rstudio.com/products/rstudio/download/#download

- R and tidyverse dependencies
  ``` 
  sudo apt-get install r-cran-curl r-cran-openssl r-cran-xml2 libxml2-dev
  ```


## 📦 R packets
1. Open RStudio -> Open Project -> student-success-analysis **.Rproj**
2. File called student-success-analysis **.Rmd** should open up, 
    - if it didn't open: navigate to it using the bottom right panel "Files" and double click the file
3. Run the first chunk in the file (Ctrl + Shift + Enter) which contains `library` functions
4. Popup will open asking you to install the packets, press yes. This step takes **~20 minutes**

## 📝 Notes:
- KS - if P = 1 that means that data surley come from same distribution. If P = 0 then data comes from different distributions
  
## 📋 Todo:
- [ ] spellcheck
- [ ] write introduction to the problem

## 🏆 Team members

<table>
  <tr>
    <td align="center"><img src="https://upload.wikimedia.org/wikipedia/commons/thumb/1/1f/Blank_square.svg/2048px-Blank_square.svg.png" width="100px;" alt=""/><br /><sub><b>Magda Radić</b></sub><br /></td>
    <td align="center"><a href="https://github.com/tprhat"><img src="https://avatars.githubusercontent.com/u/33128908?v=4" width="100px;" alt=""/><br /><sub><b>Tomislav Prhat</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/matejciglenecki"><img src="https://avatars.githubusercontent.com/u/12819849?v=4" width="100px;" alt=""/><br /><sub><b>Matej Ciglenečki</b></sub></a><br /></td>
    <td align="center"><a href="https://github.com/pdragojevic"><img src="https://avatars.githubusercontent.com/u/76600733" width="100px;" alt=""/><br /><sub><b>Petar Dragojević</b></sub></a><br /></td>

</table>