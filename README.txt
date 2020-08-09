The folder is made up of 8 jupyter notebooks files coded with Python 3.0. 

They are grouped in 4 categories:

- SCV creation files: two files dedicated to creating files. 
These files do not need to be executed for running the other programs. 
Indeed, CSV files are already created in the CSV_Creation folder.

- Statistical analysis file: one file dedicated to statistical analysis 
including graphs and regressions to discover patterns regarding the mortality 
rate and the recovery rate.

- PCA Analysis files: two files dedicated to clustering OECD members 
countries and European countries regarding the mortality rate and the recovery 
rate including Principle Components Analysis.

- Classification files: five files dedicated to classifying OECD members countries 
according their mortality rate by using countries’ features. Three classifications 
with random forest, decision tree and gradientboosting have been made and assessed 
through cross validation. A fourth file compares the two classifications. A fifth 
one deals with the improvement of the random forest. 

The two folders are containing data stored in CSV files:
 
- Sources is made up of two folders. COVID-19-master is containing useful files 
provided by John Hopkins University Center for my analysis. Data_by_country is 
containing CSV files storing the needed data for establishing the classification.

- CSV_Creation is containing two CSV files created by my Python programs. One file is
dedicated to the classification whereas another one is used for clustering and the 
statistical analysis.
