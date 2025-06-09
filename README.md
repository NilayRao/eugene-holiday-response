# eugene-holiday-response

This project explores how federal holidays affect emergency response behavior in Eugene, Oregon using CAD (Computer-Aided Dispatch) data from 2014 to 2025.

We ask:  
**Does the presence of a federal holiday significantly impact the volume, nature, and response performance of CAD-recorded incidents in Eugene?**

## What We Analyze

- **Volume**: Are fewer calls logged on holidays?
- **Nature**: Do call types shift during holidays?
- **Response Performance**:
  - How fast units respond (`secs_to_arrv`)
  - How quickly calls are closed (`secs_to_close`)

We also begin to explore whether these same trends appear within **CAHOOTS-tagged calls**, Eugene's alternative crisis response program.
---

## How to Run

- **Data Preparation Notebook**: Prepares all Data. Can run through once call data from CAD file and all class data files are read in. Creates new CSV's for use in data analysis
- **Data Analysis Notebook**: Read in all csv's. Can interchange between each dataframe to compare and contrast all incidents, cahoots specific incidents, and all incidents besides cahoots specific ones. 
