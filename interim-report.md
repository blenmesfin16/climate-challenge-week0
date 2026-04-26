Week 0 challenge Interim Report

Task 1: Git and Environment Setup

I created a github repository and named it Climate-challenge-week0.
I made the .gitignore  file in order to hide the data and csv files
I created a requirements.txt file that includes packages such as numpy, pandas,matplotlib,seaborn,spicy, jupyter and strealmit.
By creating a cy.yml file that installs requirements on every github pushes I set up Github Actions.
I included a README.md file that explains how to set up the project.
I created folders such as src,notebooks, scripts and data.
I created branches named set-up-task and set-up-task-new , committed and finally merged the set-up-task-new branch with a pull request.

Task 2: Data Profiling & Cleaning approach/plan

I will load the csv file of Ethiopia using pandas
I will add a column called country with ‘Ethiopia’
As all the -999 values indicate a missing data I will replace them all with NaN
I will check if any duplicate rows exist and delete them if I find one.
I will detect outliers in temperature, precipitation, humidity, and wind speed using Z-scores. I will consider any value having a Z-score greater than 3,as an outlier.
I will convert the YEAR and DOY columns into a proper date format as %Y%j.
I will extract Month from the date for seasonal analysis.
I will fill in any missing weather data using the previous day's value(forward fill).
I will export the cleaned data to a CSV file.
I will create time series plots, bar charts, heatmaps, and histograms to understand the data.
I will repeat the same steps for Kenya, Sudan, Tanzania, and Nigeria.
Finally I will do a comparison among all the 5 countries and rank them by climate vulnerability.
