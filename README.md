# Bloodhound
Tracker for personal metrics tracking. A self-proposed excersise to improve coding and development across a range of tools whilst still being useful (I actually track all these metrics for real!)

### Goal
Use Telegram, SQL and some other API's to store metrics related to mood, health, vehicle usage data for later analysis/usage.

#### Telegram
Has to be able to:
- receive and store images (pictures of vehicle dashboards/utility meters/etc)
- ask questions on a smart schedule (are you awake? -> ask morning routine questions)
- pop reminders for regular meditation/excersise/stretching

#### SQL 
Self hosted on NAS drive, probably will go with Postgresql or mariadb
- backups need to be in place
- robust input checks make sure wrong data isnt being inserted
- Application needs to have error recovery working properly and detect and pass on SQL issues

#### Other API interfaces
- Nintendo Parental Control -> for time spent on the nintendo switch (this will be very difficult)
- Fitbit -> sleep hours, wake up times, steps taken
- Steam/Epic hours -> for time spent on steam/epic -> posisble create own app on desktop for this.


These will be the main 'work steams'

### First deliverable
The first deliverable will be making a telegram bot which can recieve images, store them locally and update an sql table with details
