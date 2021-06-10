# matplotlib-challenge

Repository for the matplotlib homework in Week 5 of Monash Bootcamp

![Laboratory](Images/Laboratory.jpg)

## Homework Description

This homework required me to examine a real-world data-set using Python, the Pandas library, MatPlotLib library and the SciPy Stats library.

This dataset looked at a range of mice who were being treated with differtent drug regimens to observe the impact it had on tumor size within the mice.

We were required to combine two datasets to create one large table of data, then clean it of any duplicate mice and finally perform outputs from this dataset.

These outputs included a range of summary statistics, as well as bar, line, scatter, pie and box plots with which to analyse the data and draw conclusions.


## Guide to Repository

You can find the code in the Pymaceuticals folder, all code and conclusions drawn from the data are located in the Jupyter Notebook file called "pymaceuticals_starter.ipynb".

The folder named "data" contains the two csv files which hold the mouse and drug regimen data for the homework.

This ReadMe file contains the description of the homework and has also been used to track my difficulties with the homework as I cam across them to then follow up as more revision for myself.


## Challenges in Homework

### Remembering notation for .drop function in Pandas.

* Kept encountering errors with column names not found in aixs due to missing the .index from the drop function when informing the code to remove full rows.
* Reviewed previous weekly lessons to recommit to memory and solve issue.

### Remembering output type when finding duplicate mouse ID

* Duplicate mouse ID was put out as a series with an index
* Required to designate only the value inside of it when using later or got an error of comparing series with different lengths
* Resolved after determining location in output, also created print function to programmatically display duplicate mouse ID's from the dat in case there had been more than one

### Remembering notation for .aggregrate function

* Could not find in weekly lessons
* Used Google and Stack Overflow to find details
* Performed a few debug runs to get table values correct