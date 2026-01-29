# rmarkdown-template

## Purpose

Baseline template for re-creating standardized PDF Data visualization report (for community health, administrative datasets). 

## Basics

- Using Prettydoc() to format the final PDF
- Use standard packages (ggplot2, readxl, tidyverse)
- Extra: use scales (percentages)

## Steps

0. Load packages and data: `excel_sheets(path = file_path)`
1. Preprocess data: filter, merge, and clean data, rename columns
2. Aggregate data: calculate, summarize data
3. Assign visuals (p1, p2, etc)
4. Assign KPI variables (kpi1, kpi2)

Notes:
- Insert variables in paragraphs using `{r variable}` notation
