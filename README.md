# Application Life Cycle

- **Application life cycle** consists of the events that occurs between the app launch and app termination.
- SpringBoard, the app which is responsible for running the home screen of the iphone takes care of launching of the app.
- SpringBoard app takes care of app launch animation, from the time you tap on your app icon to loading and managing all the resources required to run the app.

# Application States
- There are 5 application states in which the app transitions based on user actions.

## Not Running
- The is not running or is suspended by the system

## Running/Foreground
### Active
- The app is running in foreground and is receiving events

### Inactive
- The app is running is foreground and is not receiving events. This can happen in cases when user receives phone call, etc.

## Background
- In this state, if there is some code to execute like background tasks it will execute and immediately move to the suspended state. The system takes the screenshot of the application just before moving to this state and uses that screenshot in app switch context.

## Suspended
- In this state, the app remains in the background state, like in memory and is not executing code. The system can decide to purge the app at any point without any intimation to the app. 
