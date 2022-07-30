# Custom IntroJS Mockup

## Overview

This is a very basic HTML/JS project using a custom IntroJS implementation. 

## Installation

1. Navigate to /intro.js and npm-install
2. If you are going to change any code in Intro.js, run `build:watch` so code will dynamically update and push to your project.

## How to see what code is now custom

To quickly see what files have been added/updated, run the following command in Git Bash

`git grep -l CodeAdded | xargs -n1 git blame -f -n -w | grep CodeAdded | sed "s/.\{9\}//" | sed "s/(.*)[[:space:]]*//"`

This will like the filename, line number and comment. In this case, it will look for the comment "CodeAdded" as that is what I used to flag all my changes.

## Notes   

This is a basic demo so there is some functionality I haven't worked on yet. Specifically, if you click the "Turn Off Hints" button to disable the overlay and turn off hints, in order to run/add hints to the page again, you'll need to refresh the page first.

Also, in this specific implementation (again this is one of IJS's example templates), if you click a tip you will be presented with the tip modal and when you click "done" or whever the CTA is, that specific tip dot will disappear. So you can go to each tip, click, get the tip, click the CTA, and go to the next tip OR you can click the "Turn off Hints" button on the overlay and turn off all hints and return to using the page.