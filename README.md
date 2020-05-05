# ...

This project is the final project of the Udacity Nanodegree Data Analyst. It is
based on data about Covid19 of the John Hopkins Univertity. Additional data is
retreived via the Wikipedia API.
Main goal of this project is t... Firstly data is gathered from different sources:
 ...
 Secondly the data from the different sources is visually and programmatically
 assessed to be cleaned in the next step for the final
 analysis. The analysis ...

## Quickstart
1. Install Anaconda, best with homebrew: `brew cask install anaconda `
2. To set path variable run : ```conda init```
3. Open Jupyter Notebookvwirh ```jupyter notebook```
4. In the notebook open the .ipyn-file.


## Structure

1. Gather: Data is gathered from three different sources of data as described
   in steps below:
   ...
2. Assess (visually and programmatic): Check gathered data for quality and  tidiness issues.
   - Qualitiy beeing: Completeness, Validity, Accuracy, Consistency
   - Tidiniss beeing: each variable is a column, each observation is a row, each type of observational unit is a table.
3. Clean
   - Requirements for Clean data:
     - Quality requirements:
       - Completeness: All necessary records in dataframes, no specific rows, columns or cells missing.
       - Validity: No records available, that do not conform schema.
       - Accuracy: No wrong data, that is valid.
       - Consistency: No data, that is valid and accurate, but referred to in multiple correct ways.
      - Tidiniss requirements (as defined by Hadley Wickham):
        - each variable is a column
        - each observation is a row
        - each type of observational unit is a table.
4. Analysis & Visualization
5. Store

## Dependencies
The following python libraries are used in the project:
- pandas
- NumPy
- requests
- tweepy
- json

## Known Bugs
