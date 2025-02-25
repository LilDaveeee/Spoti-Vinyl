# Spoti-Vinyl
Simple customisable application to show the current album art and other info in a spinning vinyl format either on desktop or display on top.

![image](https://github.com/user-attachments/assets/2e4e249e-79f2-49ff-9f79-c847a9f372a4)
![image](https://github.com/user-attachments/assets/0acb1a52-9821-4d36-a699-c887bfe96225)


Controls - 

1. Right click cover art to Pause/Play currently playing.
2. Left click on either left or right side of album art to skip or go back a song.
3. Middle click on album art to switch it between showing on top of everything as an overlay or being a desktop widget.

   
Installation - 

1. Download Files, exe from release and .env from source
2. Configure .env file to your liking, by default there are no shortcuts/hotkeys, if you want hotkeys simply add ctrl+right to SKIP_HOTKEY, if you want control + right arrow to skip a song.
3. Client ID and Client Secret need to be configured to use yours https://developer.spotify.com/dashboard, Create an app, name and description are personal to you however callback should be http://localhost:8888/callback
4. Monitor is counted from 0 so if you have multiple monitors your primary display will be 0, not 1
