# EDA

The EDA_Student_Submissions.ipynb is a Python Notebooks containing Exploratory Data analysis of data provided in 'grades.csv' file. This has 2 columns, which have submission URL in one column and submission time including date in another.

The exercise was to add more columns using data-driven technique to extract the 
1. Format of the file uploaded from URL, and find out which was the most used format.
2. Given the first deadline as 03-March-2017, 11:59:59 PM and second one as 9-Mar-2017, 11:59 PM which deadline was met (derived info- first\second\missed)
3. On which date and time did the max submissions happen and on what slot of the day like- Morning, Afternoon, Late Evening, Other(Derived column) etc.

Libraries used:
1. Python pandas dataframe to convert the data in a analysis suitable format.
2. Datetime libraries of python were made use to extract date, time and do the data comparison.
3. Searborn Libraries were made use of to plot a bar chart for analysis. 