# Crime_Time_Final_Project

## Communication Protocol (Week 1):
As we are still getting things figured out for our project, these requirements will probably be specific to week 1. Expect a more consistent schedule to be built later.

* Team will meet every Monday and Wednesday at normal class time.
* Team will determine before ending each Zoom session when all members are able to meet outside of class times via Zoom.
* Team will use group slack channel to continually update each other as to status or ask questions of each other when stuck.

## Deliverable 1 Requirements:
### General Requirements
Team members have drafted their project, including the following:

- [X] Selected topic
- [X] Reason why they selected their topic 
- [X] Description of their source of data
- [X] Questions they hope to answer with the data

---

### GitHub Requirements:
Main Branch
- [X] Includes a README.md

README.md must include:
- [X] Description of the communication protocols
- [X] At least one branch for each team member
- [ ] Each team member has at least four commits from the duration of the first segment

**Note**: The descriptions and explanations required in all other project deliverables should also be in your README.md as part of your outline, unless otherwise noted.

--- 

### Machine Learning Model Requirements:
- [ ] Takes in data in from the provisional database
- [ ] Outputs label(s) for input data

---

### Database Requirements:
- [ ] Sample data that mimics the expected final database structure or schema
- [ ] Draft machine learning module is connected to the provisional database

## Project Overview

The City of Chicago has a long history of crime. The overall crime rate is higher than that of the national average. In fact, the chance of becoming a victim of either a violent crime or property crime in Chicago is 1 in 28 [(Reference)](https://www.neighborhoodscout.com/il/chicago/crime#description).  Unfortunately, many crimes reported do not result in an arrest. This project examines crime data reported in the city of Chicago from 2010 to present to determine if an arrest for a crime can be predicted based on location, time, and crime perpetrated.

## Reason

Several members of the team expressed an interested in researching in the broad area of crime. We discussed several options for locations and eventually settled on Chicago. When looking at the data file, we observed that there are many crimes reported that result in no arrests. Thus, we decided to try to build a machine learning model that can be used to predict arrest rate based on location, time, and/or type of crime committed.

## Team Members

Randy Melancon [branch](https://github.com/profweston/Crime_Time_Final_Project/tree/randys-branch)\
Matthew Parrish [branch](https://github.com/profweston/Crime_Time_Final_Project/tree/mparrish)\
Jarod Peters [branch](https://github.com/profweston/Crime_Time_Final_Project/tree/jarodpeters)\
Andres Rosas [branch](https://github.com/profweston/Crime_Time_Final_Project/tree/andres)\
Melissa Weston-Puett [branch](https://github.com/profweston/Crime_Time_Final_Project/tree/mels-branch)

## Data Source and Preprocessing

The data for this project was retrieved from Data.gov and was published by The City of Chicago. There were # crimes reported and includes information about X. Data were filtered or dropped during the preprocessing with Pandas using the following criteria:

1. Data were filtered by date to include years 2015 and forward.
2. Rows including NaNs and empty cells were deleted.
3.
4. 

## Database

## Machine Learning Model
Our provision Machine Learning Model is the Random Forest Classifier. We chose a supervised learning model because we are attempting to predict arrests based on data from previous arrests. Since our target variable only has two possible values (True or False), it is a classification model. The Random Forest Classifier is beneficial because it is robust against overfitting, can handle many input variables without variable deletion, and can run efficientily on our large dataset.



## Results

## Tableau Interactive Dashboard
The team is working to create an intereactive dashboard in Tableau that will be used during a presentation to governemnt officials in Chicago.  The goal is to provide the following data on the dashboard:
* A bubble chart to show the types of crimes that can be filtered by distrcit or year.
* A heat map that shows crimes by district that can be filtered by the type of crime, year, and whether or not an arrest was made.
* A chart to show the arrest rates filtered by year and type of crime.
* A chart to show the trends over time for each district that can be filtered by the type of crime.
* A line chart to show the times that crimes are committed and filtered by whether or not an arrest was made.

The group will then present a recommendation to the city council based on the results of the data analysis.
## Summary

Google slide link:
