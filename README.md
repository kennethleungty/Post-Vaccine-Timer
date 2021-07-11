# Post Vaccine WaitTime Tracker

## Motivation
- After administering a COVID-19 vaccine dose, the patient is to wait 30 minutes at a designated waiting area for observation (monitor any post-vaccine side effects)  
- The nurse administering the dose will need to chart the end of the wait-time (i.e. 30 minutes after the dose is administered) on the patient's vaccine card  
- Due to documentation requirements, the end time will need to rounded up to the nearest 5-min intervals  
- For example, if the dose is administered at 1:11pm, the end time to be documented is 1:35pm, and NOT 1:31pm  
- This has resulted in plenty of hassle and confusion from the mental calculation  


## Solution
- Developed a simple web app (using Python Flask and vanilla Javascript) to create a running waittime tracker  
- Deployed on Heroku: https://bit.ly/vaccine-waittime
- The web waittime tracker clearly indicates to the user what is the (rounded up) time to chart on the vaccine card  
- This means that the nurse just needs to look at the web tracker to see the end time, and copy it for documentation (No need for mental calculations anymore)  
