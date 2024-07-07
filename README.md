# E-Commerce Data Analysis

## Overview

This project is aimed at achieving real-world results by using raw data from an E-commerce type of company to exploit my skills using Pandas (python) to organize, format, explore and clean data. In this project, I had the chance to explore assumptions, generate findings, and ultimately provide a summary of the data provided. In this file I will detail the process I went through in order to achieve the results provided.

## Data Analysis

Step 1: Data Exploration

- My initial interest in the data was understanding the company from an average perspective.
  - How much the average prouct sold for.
  - How much the average product cost.
  - How much the average product weighed.
  - Most sold subcategory

## Data Cleaning Process

During this analysis, data cleaning was used to simplify the numbers in the DataFrame. Using a lamba function **dollar_to_millions(x)**:
x ⇢ the function requires a dataframe to be passed through.
return

    | Part of Function    | Description/Use Case                             |

| ----------------- | ----------------------------------------- |
| **(x)** | the function requires a dataframe to be passed through.
return
|
| **Returns** | Scaled Data and Formated Columns:

- Each value in dataframe is divided by 1 Million to simplify numbers.
- Column names are renamed to adjust |

* **(Lambda Function)** dollar_to_millions(x)
  - **x ⇢** Requires a DataFrame of int/float values to be passed in.
  - **Returns ⇢** Scaled Data and Formated Columns
    - Scaled and Format Data - With the use of a lambda function, the data was scaled (each value divided by one million) and formatted (adding $ in front of the value and M representing million after the value).
    - Clear Column Names - Using the pandas .rename() function, provided a uniform way to rename each column name to a more suitable name that matches the updated data.

#### Screenshots: Data Cleaning Process

| DataFrame Type    | Image Example                             |
| ----------------- | ----------------------------------------- |
| Orignal DataFrame | <img src="./Screenshots/original_sc.png"> |
| Final DataFrame   | <img src="./Screenshots/final_sc.png">    |

## Project Files

📂 **Resources**  
📂 **Screenshots**  
ℹ️ **README.md**  
🎬 **wholesale_data_analysis_starter_code.ipynb (Jupyter Notebook and VS Code accepted)**

## Instructions

1. Clone repository [Project Repository](https://github.com/ncmoliver/pandas-challenge-1..git)
2. Open Project Folder (panda-challenge-1)
   - open wholesale\_

## References

[Markdown CheatSheet](https://www.markdownguide.org/cheat-sheet/) - Used for proper Markdown Syntax.
