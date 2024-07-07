# E-Commerce Data Analysis

## Overview

This project is aimed at achieving real-world results by using raw data from an E-commerce type of company to exploit my skills using Pandas (python) to organize, format, explore and clean data. In this project, I had the chance to explore assumptions, generate findings, and ultimately provide a summary of the data provided. In this file I will detail the process I went through in order to achieve the results provided.

## Data Analysis

## Data Cleaning Process

During this analysis, data cleaning was used to make the findings clear. the data is an important part in making the result/findings clear.

- **(Function)** dollar_to_millions(x)
  - **x** : Requires a DataFrame of int/float values to be passed in.
  - **Returns ⇢**: Scaled Data and Formated Columns
    - Scaled and Format Data - With the use of a lambda function, the data was scaled (each value divided by one million) and formatted (adding $ in front of the value and M representing million after the value).
    - Clear Column Names - Using the pandas .rename() function, provided a uniform way to rename each column name to a more suitable name that matches the updated data.

#### Screenshots: Data Cleaning Process

| DataFrame Type    | Image Example                             |
| ----------------- | ----------------------------------------- |
| Orignal DataFrame | <img src="./Screenshots/original_sc.png"> |
| Final DataFrame   | <img src="./Screenshots/final_sc.png">    |

## References

[Markdown CheatSheet](https://www.markdownguide.org/cheat-sheet/) - Used for proper Markdown Syntax.
