# Froxcey Sidebar

**This project is currently inactive, meaning it will not receive any updates.** The reason is that I coded this for myself, but I don't use Übersicht anymore. I will still read and respond to issues.

## About 

A Übersicht widget that adds IP display and YouTube download button to your desktop. Just hover your mouse to the very right, and you will see everything. Click on the ip address to copy it. Simply copy a YouTube video link and click on either mp3 or mp4, then the video or music will be ready in your download directory.

## Requirement

To make the download process work, you need to install FFmpeg and youtube-dl. You can use homebrew commands:

`brew install ffmpeg`

`brew install youtube-dl`

Alternatively, you can donwload them from here. [FFmpeg](https://www.ffmpeg.org/) [youtube-dl](https://youtube-dl.org/) 

You might also need to enable "Load Bash Env" in Übersicht by going to menubar > Übersicht > Preferences and disable send to background (enable interaction) by going to  menubar > Übersicht > Froxcey Widget > uncheck "Send to Background"

If you don't have Übersicht, click [here](https://tracesof.net/uebersicht/)

## Known Issues

Sometimes there's a bug with the widget, and you might need to click on menubar > Übersicht > Show Debug Console and click on menubar > Übersicht > Refresh All Widgets, then it would magically work (neither do I know why this problem occurs).

There are some unfixable render error.

## Installation

1. Download and unzip FroxceySidebar.widget.zip
2. Click on menubar > Übersicht > Open Widget Folder
3. Drag FroxceySidebar.widget into the folder (under widgets folder)
4. Enjoy -ˬ-

## Configuration

I'm planning on adding more configuration, but for now, I only offer sensitivity. Go to menubar > Übersicht > FroxceySidebar-widget-index-jsx > Edit, and you should now be able to edit the file. You should see on line 2:

`HoverWidth: 10,`

Simply change the 10 to whatever you want. Unit: pixels. This defines the range of hover detection (from right).

## Upcoming Features

- Bug Fixes
- YouTube playlist download
- Better YouTube download quality
- Better UI
- Key Modifier

##  Contribution

Sorry this is a very early code I made, and it is quite messy and large. If you can offer any contribution,  I would be gladly accept it. I'm still in high school, so I cannot work on this too often, but I'm trying to maintain this project the best I can.
