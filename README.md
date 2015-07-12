Compare Side-By-Side
================
This package adds a simple side-by-side comparison tool to Sublime Text 2 and 3.

![Screenshot](http://dougty.com/files/SBSCompareScreenshot.png)

Features
---
  - Easily select two open tabs to compare
  - Comparison results open in a new window
  - Empty lines added so common code lines up
  - Count number of lines changed
  - Highlighting of changed lines
  - Synchronized scrolling

Installation Options
---
  - Search for and install using [Package Control](https://sublime.wbond.net/installation) (ctrl+shift+P, "Install Package")
  - Clone or extract this repo to a new folder in your Sublime 'Packages' folder (*Preferences -> Browse Packages*)

Usage Options
---
  - Right click on a tab and select "Compare with..."
  - Right click somewhere in the active view and select "Compare with..."
  - Right click on a tab and select "Compare with active tab"
  - Highlight text, right click -> "Mark selection for comparison"
   - Mark a second selection, then right click -> "Compare selections"
  - Create two selections by holding CTRL, then "Compare selections"
  
Configuration
---
  - Highlight colours and other options can be configured in SBSCompare.sublime-settings
  - To access: *Preferences -> Package Settings -> Compare Side-By-Side*
  - Default colours are optimized for the base16 colour scheme in ST3
