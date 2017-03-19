This project contains a Tasker (Android) task used for interactive notifications from the SmartThings CoRE SmartApp.

1. Obtain CoRE URL
    a. Open CoRE SmartApp
    b. Click on CoRE Dashboard
    c. Copy the URL to the clipboard
2. Setup Tasker
    a. Import the _CoRE Notifier_ task into Tasker.
    b. Import the _SmartThings SMS_ profile into Tasker
    c. Run the _CoRE Notifier_ task, which will prompt for CoRE URL
    d. Paste URL obtained in step 1, replacing `/dashboard#/` with `/ifttt` _(Note: No trailing slash!)_
    e. Submit
    
To display a notification, send yourself an SMS from CoRE using the following format:

@CN|Title|Text|Label1|Callback1|Label2|Callback2|Label3|Callback3

Notification actions are specified by a label and callback pair. The task supports up to three notification actions.