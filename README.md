# Eugene Emergency Response during Federal Holidays

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

- **Data Preparation Notebook**: Prepares all Data. Initially, all class data csv's are in a folder called time. Call_Data_from_CAD is in the same directory as the notebooks. You can run through the entire notebook once call data from CAD file and all class data files are read in. Creates new CSV's for use in data analysis
- **Data Analysis Notebook**: Read in all csv's created in the data preparation notebook. Each csv is read into a specific dataframe. You can change between each dataframe to compare and contrast all incidents, cahoots specific incidents, and all incidents besides cahoots specific ones. As the notebook progresses, more aspects of the project are revealed.
