# Bug Report Document 


**Title:** System doesn’t update new uploaded dataset at real time

**ID:** BR10

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Major

**Priority:** Medium

**Steps to Reproduce**
1.	User get to visualisation module 
2.	User upload supported dataset 
3.	User choose a plot
4.	User choose Feature/ Column for each required axes from the plot
5.	User click "Plot" button
6.	User change uploaded dataset
   
**Expected Result:** New dataset features should be updated in dropdown menus.

**Actual Result:** Previous dataset features are kept with no real time update.

**Date Reported:** October 24, 2024

________________________________________



**Title:** Dropdown menus doesn’t reflect required data type depending on plot 

**ID:** BR11

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Major

**Priority:** High

**Steps to Reproduce**
1.	User get to visualisation module 
2.	User upload supported dataset has numerical & categorical features
3.	User choose a plot requires both axes numeric (scatter / line)
4.	User choose Feature/ Column for each required axes from the plot
5.	User click "Plot" button

**Expected Result:** Only numeric columns should appear in the dropdown menu, as both axes require numeric values.

**Actual Result:** Both numeric & categorical values appeared. 


________________________________________
**Title:** Dropdown menus doesn’t reflect required data type depending on plot 

**ID:** BR12

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Major

**Priority:** Medium

**Steps to Reproduce**
1.	User get to visualisation module 
2.	User upload supported dataset has numerical & categorical features
3.	User choose a plot requires both numeric & categorical axes (Barchart)
4.	User choose Feature/ Column for each required axes from the plot
5.	User click "Plot" button

**Expected Result:** The X-axis dropdown should show categorical columns, and Y-axis dropdown should show numeric columns.

**Actual Result:** Both axes have both data types. 

________________________________________

**Title:** Missing Error Handling when choosing mismatched plot

**ID:** BR13

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Major

**Priority:** High

**Steps to Reproduce**
1.	User get to visualisation module 
2.	User upload supported dataset has only categorical features
3.	User choose a plot requires both axes numeric 
4.	User choose Feature/ Column for each required axes from the plot
5.	User click "Plot" button
   
**Expected Result:** An error message should appear in the dropdown indicating that there are no available numeric columns.

**Actual Result:** No Error Message, process completes normal.

**Note:** Validation missing, may cause misleading results. 
________________________________________


**Title:** Zoom In not  functioning for plots

**ID:** BR15

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Minor

**Priority:** Low

**Steps to Reproduce**
1.	User get to visualisation module 
2.	User upload supported dataset has both categorical & numeric features
3.	User choose a plot 
4.	User choose Feature/ Column for each required axes from the plot
5.	User click "Plot" button
6.	User click “Zoom In” icon below plot

**Expected Result:** Plot should be Zoomed In

**Actual Result:** Nothing happens. 
________________________________________

**Title:** Missing Validation for downloading cleaned data more than once

**ID:** BR25

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Minor

**Priority:** Low

**Steps to Reproduce**
1.	User get into Cleaning Module 
2.	User Upload supported dataset
3.	User apply any cleaning option
4.	User click "Download" button
5.	User Choose File destination
6.	User Click "Save"
7.	User click "Download" button again

**Expected Result:** A Validation Message appears “Dataset already downloaded, Are you sure you want to download again?” 

**Actual Result:** Data is downloaded twice without any validation messages. 

**Note:** Validation missing

________________________________________

**Title:** Missing Validation for downloading already cleaned data 

**ID:** BR26

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Minor

**Priority:** Low

**Steps to Reproduce**
1.	User get into Cleaning Module 
2.	User Upload already clean supported dataset
3.	User click "Download" button
4.	User Choose File destination
5.	User Click "Save"

**Expected Result:** A Validation Message appears “Dataset alreadyClean, Are you sure you want to download?” 

**Actual Result:** Data is downloaded without any validation messages. 

**Note:** Validation missing

________________________________________

**Title:** Missing Error Handling when applying Handling Consistency option with no column choice 

**ID:** BR29

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Minor

**Priority:** Low

**Steps to Reproduce**
1.	User get into Cleaning Module 
2.	User Upload supported dataset with at least consistent column
3.	User click “Drop” button
4.	User don’t choose column to handle from the available dropdown menu 

**Expected Result:** An Error Message appears as no column selected for handling

**Actual Result:** System is not proceeding, but no Error Message 

**Note:** Error message only missing with correct procedure

________________________________________

**Title:** Missing Error Handling when applying Handling Missing option with no column choice 

**ID:** BR34

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Minor

**Priority:** Low

**Steps to Reproduce**
1.	User get into Cleaning Module 
2.	User Upload supported dataset with at least missing row
3.	User doesn't choose column to handle from dropdown menu
4.	User choose to Drop/ Fill/ Keep
5.	User click "Apply"

**Expected Result:** An Error Message appears as no column selected 

**Actual Result:** System is not proceeding, but no Error Message 

**Note:** Error message only missing with correct procedure

________________________________________

**Title:** Missing Error Handling when applying Handling Missings option with no specific option choice 

**ID:** BR35

**Environment:** Windows 11Pro, Version 23H2 (OS Build 22631.4317)

**Severity:** Minor

**Priority:** Low

**Steps to Reproduce**
1.	User get into Cleaning Module 
2.	User Upload supported dataset with at least missing row
3.	User choose column to handle from dropdown menu
4.	User click "Apply" without choosing option

**Expected Result:** An Error Message appears as no selected handling option 

**Actual Result:** System is not proceeding, but no Error Message 

**Note:** Error message only missing with correct procedure

