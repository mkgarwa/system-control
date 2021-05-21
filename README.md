# system-control

Sleep, Restart & Shutdown icons with title on right side of the desktop.

![Screenshot](/screenshot.png)


Ref: http://tracesof.net/uebersicht-widgets/#grid-launcher

# Installation

Add the widget to Übersicht's widget folder.

Customize styles and links to match your preferences in the index.coffee.

Remember to enable interactions with the widget through Übersicht's preferences.

# Extra Commands to use

**Shut down without showing a confirmation dialog:**

`osascript -e 'tell app "System Events" to shut down'`

**Shut down after showing a confirmation dialog:**

`osascript -e 'tell app "loginwindow" to «event aevtrsdn»'`

**Restart without showing a confirmation dialog:**

`osascript -e 'tell app "System Events" to restart'`

**Restart after showing a confirmation dialog:**

`osascript -e 'tell app "loginwindow" to «event aevtrrst»'`

**Log out without showing a confirmation dialog:**

`osascript -e 'tell app "System Events" to  «event aevtrlgo»'`

**Log out after showing a confirmation dialog:**

`osascript -e 'tell app "System Events" to log out'`

**Go to sleep (pmset):**

`pmset sleepnow`

**Go to sleep (AppleScript):**

`osascript -e 'tell app "System Events" to sleep'`

**Put displays to sleep (10.9 and later):**

`pmset displaysleepnow`
