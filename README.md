<h1 align="center">E-Commerce Data Analysis</h1>

<p align="center">
  <img src="readmeBanner.gif" width="800" height="400">
</p>

## Table of Contents

[Overview](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-overview)  
[Instructions](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#%EF%B8%8F-instructions)  
[Data Analysis](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-data-analysis)

- [Data Exploration](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#data-exploration)
- [Most Entries](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#most-entries)

[Data Cleaning Process](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-data-cleaning-process)  
[Data Cleaning Process: Screenshots](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-data-cleaning-process--screenshots)

- [Original DataFrame](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#original-dataframe)
- [Final DataFrame](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#final-dataframe)

[Project Files](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-project-files)  
**📄 Files**  
[wholesale_data_analysis_starter_code.ipynb](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-wholesale_data_analysis_starter_codeipynb-file)  
[README.md](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-readmemd-file)  
**📂 Folders**  
[Resources](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-resources-folder)  
[Screenshots](https://github.com/ncmoliver/pandas-challenge-1./blob/main/README.md#-screenshots-folder)

## ✨ Overview

This project is aimed at achieving real-world results by using raw data from an E-commerce type of company to exploit my skills using Pandas (python) to organize, format, explore and clean data. In this project, I had the chance to explore the data, generate findings, perform calculations, analyze the data and provide a summary of the result findings. This file is a detailed description of the process I went through in order to achieve this project. Hope you enjoy!

## 🗺️ Instructions

1. Clone repository [Project Repository](https://github.com/ncmoliver/pandas-challenge-1..git)
2. Open Project Folder (panda-challenge-1)
   - Open wholesale_data_analysis_starter_code.ipynb
   - Select the ▶️ "Run All" and the program will do the work from there 😏

## 🔍 Data Analysis

#### Data Exploration

My initial interest in the data was understanding the company from an average perspective.

- How much the average prouct sold for.
- How much the average product cost.
- How much the average product weighed.
- Most sold subcategory + additional metrics

#### Most Entries

- Identified the _category_ and _sub-category_ with the most order entries.
- Identfied the top 5 clients with the most orders (Client ID and # of orders).

## 🧺 Data Cleaning Process

✓ Data cleaning was used to simplify the numbers in the DataFrame.  
✓ Using a lamba function **dollar_to_millions(x)**:

| Parts of the Function | Description/Function                                                                                                                                                                                             |
| --------------------- | ---------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------------- |
| **(x)**               | the function requires a dataframe to be passed through.                                                                                                                                                          |
| **Returns**           | Scaled Data and Formated Columns: Each value in dataframe is divided by 1 Million to simplify visibility of numbers. Values are formatted to represent the appropiate currency ($) and ratio of data (Millions). |

<hr>

## 📷 Data Cleaning Process : Screenshots

### Original DataFrame

<img src="./Screenshots/original_sc.png" width="600">

### Final DataFrame

<img src="./Screenshots/final_sc.png" width="600">

## 💼 Project Files

#### 📄 Run File - wholesale_data_analysis_starter_code.ipynb

Run file where data cleaning, calculations, and analysis are performed.

- Requires an editor that can run Pandas packages
- Suggested editors: Jupyter Notebook / VS Code

#### 📄 README.md

- Information file: Find more information about project/analysis, such as run instructions, screenshots, and more.

#### 📁 Resources (folder)

- client_dataset.csv : Raw csv file with E-commerce purchase order data.

#### 📁 Screenshots (folder)

- original_sc.png: Used in Readme.md - Original DataFrame
- final_sc.png: Used in Readme.md - Final DataFrame

## 🐻‍❄️ Use of Pandas In Project

- Explore DataFrame for a better understanding of data.
- Format and renamed columns.
- Perform calcualtions (total weight, subtotal, etc. )
- Created new dataframes out of existing dataframes
- Concatenate two dataframes
- Used a lamba function to format and simply numeric dataframe

## 🔬 Findings

- The companies top product category was the consumables category, with bathroom supplies being the most purchased consumable.
- The compnaies top client is client 33615, which brought in a Net Profit of $36.58 Million dollars with 64, 313 units purchased.

## References

Online Tutor | **Emmanuel Mpwanga** | Provided helpful assistanced through the duration of the first half of the project.  
[Markdown CheatSheet](https://www.markdownguide.org/cheat-sheet/) - Used for proper Markdown Syntax.  
[Xpert Learning Assistant](https://bootcampspot.instructure.com/courses/6028/external_tools/313) - Used to assist in debugging, problem solve, and in learning & practicing different methods.
