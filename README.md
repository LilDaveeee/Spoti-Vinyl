# Spoti-Vinyl
Simple customisable application to show the current album art and other info in a spinning vinyl format either on desktop or display on top.


Installation - 
1. Download Files
2. Configure .env file to your liking, by default there are no shortcuts/hotkeys, if you want hotkeys simply add ctrl+right to SKIP_HOTKEY, if you want control + right arrow to skip a song.
3. Client ID and Client Secret need to be configured to use yours https://developer.spotify.com/dashboard, Create an app, name and description are personal to you however callback should be http://localhost:8888/callback
4. Monitor is counted from 0 so if you have multiple monitors your primary display will be 0, not 1
