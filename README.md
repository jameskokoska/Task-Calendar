# Googley Calendar
Turns your Google Calendar into a task list. It can be used here: <a href="https://jameskokoska.github.io/GoogleyCalendar/">https://jameskokoska.github.io/GoogleyCalendar/</a>

# Features
* Sync to your Google Calendar, with up to 2 calendars supported
* Mark tasks as completed/incomplete
* Stored this information inside Google Calendar with emoji
* Identify course codes in event names
* Display information in a pleasing way
* Custom animations
* Color coded courses
* Support for description of events
* Overdue events become red
* Support for 'all day' events
* 7 day view dynamically adjusts to use specification for 'Number of days to view setting'
* Can mark tasks as complete in 7 day view
* Sort information based on Course/Completed/Task Name/Date set
* Save settings to web browser cache
* Save last preferred sorting method
* Specify number of events to load
* Specify number of days to view tasks from
* Load events before the current time (specify in settings)
* Refresh and sync new data from your Google Calendar
* Error detection when session times out

# Create and run a local copy
### Setting up API Keys
1. Setup Google API Keys 
2. Create file in root of project (i.e. ```.\googleycalendar\```) called ```apiGoogleconfig.json```
3. Get ```clientId``` and ```apiKey``` from Google Developers website and pass in the following format into the JSON file:
```
{
    "clientId": "",
    "apiKey": "",
    "scope": "https://www.googleapis.com/auth/calendar",
    "discoveryDocs": ["https://www.googleapis.com/discovery/v1/apis/calendar/v3/rest"]
}
```

### First Time Install
Ensure React and NPM is properly installed
1. ```cd .\googleycalendar\```
2. ```npm install```

### Running development server after install
1. ```cd .\googleycalendar\```
2. ```npm start```
3. open ```localhost:3000``` in preferred web browser