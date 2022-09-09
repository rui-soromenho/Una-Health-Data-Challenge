# Una-Health-Data-Challenge

Project description

This dataset was provided by Una Health.
The main objective of this data challenge is to visualise blood glucose levels and find connections between the blood glucose levels and tracked meals.


## Data
The data consists of:

A csv file with the historic blood glucose levels of the patient: levels_all.csv . We're interested in blood glucose readings which have an Aufzeichnungstyp of either 0 or 1 (those appear in different columns because they are different types, automatically collected every 15 minutes vs. manual scanned by the patient, but are readings from the same sensor and thus should be treated as such). The blood glucose reading is noted in Glukosewert-Verlauf mg/dL or Glukose-Scan mg/dL . All timestamps noted in this file are UTC.
A csv file with the tracked meals of the patient: activities_all.csv . Each meal is identified by a UUID.
You can download the sample data from here: https://s3-de-central.profitbricks.com/una-health-data-challenge/una-health-data-challenge.zip

## Tasks
### Visualise
Create plots for the historic blood glucose level by each patient and the historic blood glucose level after meals (we usually look at timestamp_start of the meal + 3 hours worth of data). Feel free to group and slice the data for the individual meals as you see fit.

### Interpret
What conclusions can you draw when looking at the combined data of historic blood glucose levels and tracked meals for an individual patient and for certain meal types of an individual patient? What clusters (if any) do you find? What additional information (if any) do you need? What clustering methods would you apply?

### Evaluation Criteria
#### General: 
Selected and explained chosen software design and libraries, used clean code structure, followed and explained coding conventions
Algorithms and data structures: explained the approach and thinking and methods used, clarified variety and suitability of methods and algorithms used, explained selected data structure
#### Documentation: 
Added clear inline & high-level documentation, added documentation on how to start & run the submitted solution
We evaluate your communication with us
