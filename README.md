# R-ALAB-308.4.1
Overview
This script is designed to process CSV data, perform operations on it, and transform it into a structured JavaScript object array. Additionally, the script calculates the average age from the provided data.

Input
The input to this script is a CSV string stored in the csvString variable. It assumes a standard CSV format with a header row containing column names and subsequent rows containing data.

Steps
Get the number of columns from the first row
Initialize the array
Loop through each row
Check if the number of cells in the row matches the number of columns
Add the row to the array
Get the headings from the first row
Initialize the array to store the objects
Loop through each row starting from the second row
Loop through each cell in the row
Add the object to the array
Insert an object at index 1
Add an object to the end of the array
Initialize the sum of ages
Loop through each object in the array
Calculate the average age
Log the array of objects and the average age
Transform the final set of data back into CSV format
