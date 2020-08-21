# Data Collection

## Collects required sleep data

It delivers the relevant data required for manupulation of data
For report generation.

## Working Google Fit api

### Scenario: Get sleep data from the Google Fit api

  Given It requires a http framework from which one can request and get corresponding response.

  When I request user sleep data from Google fit api.

  Then I get the data in the json format with all the required fields in it.

### Scenario: Extract relevant data from the JSON of sleep data

  Given user sleep data in JSON format.
  
  When I traverse through the data.
  
  Then I get and save the endTimeMillis, startTimeMillis and activityType.
