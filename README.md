# slack-desktop-dark-theme
My Frankensteined CSS to add a dark theme to the Slack desktop app, based on [slack-black-theme](https://github.com/d-fay/slack-black-theme).

## Installation

Navigate to the Slack desktop installation directory:
* Windows: `%localappdata%\slack\`
* Linux: `/usr/lib/slack/`
* MacOS: `/Applications/Slack.app/Contents/`

Open up the most recent version (e.g. app-3.1.1) then open resources\app.asar.unpacked\src\static\index.js and resources\app.asar.unpacked\src\static\ssb-interop.js

At the very bottom of both files, add the contents of [loader.js](loader.js).
