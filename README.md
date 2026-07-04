# Audible Data Cleaning Project

## Project Overview
This project focuses on cleaning an Audible audiobook dataset using Microsoft Excel Power Query. The main goal was to convert messy raw data into a clean, structured, and analysis-ready dataset.

## Tools Used
- Microsoft Excel
- Power Query Editor
- Data Cleaning
- Data Transformation

## Dataset Columns
The original dataset included these columns:
- name
- author
- narrator
- time
- releasedate
- language
- stars
- price

## Cleaning Tasks Performed
1. Standardized the `name` column using proper title casing.
2. Removed prefixes like `Writtenby:` from the author column.
3. Split multiple authors into separate columns.
4. Converted `releasedate` into a consistent date format.
5. Converted audiobook `time` from text into duration format.
6. Cleaned the `price` column and converted it into numeric format.
7. Extracted numeric rating values from the `stars` column.
8. Split multiple narrators into separate columns.
9. Created a new `releaseinfo` column by merging release date and language.
10. Formatted price values consistently with two decimal places.


## Project Learning
This project helped me understand how to clean real-world messy data using Power Query, handle errors, convert data types, and make better decisions while working with null and zero values.
