# Post Vaccine WaitTime Tracker

## Motivation
- After receiving a COVID-19 vaccine dose, the patient is to wait >=30 minutes at a designated waiting area for observation (monitor any post-vaccine side effects)  
- The nurse administering the dose will need to chart the end of the wait-time (i.e. 30 minutes after the dose is administered) on the patient's vaccine card  
- Due to documentation requirements, the end time will need to rounded up to the nearest 5-min interval  
- For example, if the dose is administered at 1:11pm, the end time to be documented is **1:45pm**, and **NOT 1:41pm**  
- This need for mental calculation has resulted in plenty of hassle and confusion for the nurses  


## Solution
- Developed a simple web app (using Python Flask and vanilla Javascript) to create a running post-vaccine waittime tracker  
- Deployed on Heroku: https://bit.ly/vaccine-waittime
- The web wait-time tracker clearly indicates to the nurses what the (rounded up) time to chart on the vaccine card is  
- This means that the nurse just needs to refer to the web tracker on the computer screen to see the end time, and then transcribe it directly for documentation (No need for mental calculations)  
