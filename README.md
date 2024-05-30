# File-Format-Converter

## Overview
This project aims to optimize data engineering pipelines by transforming CSV files sourced from a MySQL database into JSON format. JSON's versatility and compatibility make it an ideal choice for downstream applications. By converting CSV files to JSON, we aim to streamline data processing and enhance overall pipeline efficiency.

## Objective
The goal of this project is to enhance the efficiency of our data engineering pipelines by converting CSV files sourced from a MySQL database into JSON format. JSON is preferred for downstream applications due to its flexibility and compatibility. This project focuses on the conversion of CSV files to JSON files to facilitate smoother data processing.

## Database Design
![2023-05-26_09-51-15-b44475f68043ebe48cc1f14ef90afdb8](https://github.com/harshh351998/File-Format-Converter/assets/35166367/f4fb3279-d542-46a2-ad28-8c9dffa6146b)


## Project Design
![image](https://github.com/harshh351998/File-Format-Converter/assets/35166367/ec02b5c9-097c-4f58-a1d6-2fc3c6e8de8f)

## Validation Steps:

### 1. Verify Creation and Population of Target Folder:
   - Confirm that the target folder for JSON files has been created.
   - Ensure that the folder is populated with JSON files.
   - Validate that the schema structure reflected in the JSON files accurately represents the data from the CSV files. (Hint: Refer to schemas.json for comparison.)

### 2. Record Count Verification:
   - Obtain the count of records in the original CSV files.
   - Count the number of records in the converted JSON files.
   - Compare the count of records in the CSV files to the count of records in the JSON files.
By performing these validation steps, you can ensure the successful conversion of CSV files to JSON format and verify the accuracy of the data transformation process.

## Technology
1) Programming Language – Python
2) Pandas – For Converting CSV to Dataframe and then Dataframe into JSON.
