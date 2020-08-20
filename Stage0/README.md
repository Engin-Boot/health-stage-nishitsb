# The Essentials

1. Breakdown the problem into modules. Name each module
1. Rename the 'give-me-a-name...' files to reflect the module names.
Create more files for more modules.
Fill the responsibility and acceptance-criteria in each module.
1. Fill the sequence-start file with the details of module-interactions,
as indicated in that file.

## The first use-case

Consider the first use-case to collect sleep-data and present it to a doctor
(e.g., to treat insomnia)

Consider that the patient has a device that's compatible with Google Fit:
```json
{ 
    "startTimeMillis": "<startTime>", 
    "endTimeMillis": "<endTime>", 
    "version": 1, 
    "activityType": 72 // Sleep 
} 
```
See the [Google Fit documentation](https://developers.google.com/fit/scenarios/write-sleep-data)
for more details.
