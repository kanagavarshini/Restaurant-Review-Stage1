# Restaurant review stage1
--------------------------------------------------------------------------------
## Table of Contents
--------------------------------------------------------------------------------

+ Description of Project
+ Installation / getting started
+ Instructions
+ Dependencies
+ Resources


## Project Overview: Stage 1
-------------------------------------------------------------------------------
For the **Restaurant Reviews** project, **Stage One**, I took a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. I also add a service worker to begin the process of creating a seamless offline experience for your users.

## Installation/Getting started
--------------------------------------------------------------------------------
1. Clone the project from Github
2. Run server via terminal with "$ python -m http.server"
     + In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.
     + In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`. If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.
     + With your server running, visit the site: `http://localhost:8000`, and look around for a bit to see what the current experience looks like.

## Dependencies
--------------------------------------------------------------------------------
This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

## Resources
--------------------------------------------------------------------------------
+ Service Workers: An Introduction via Google
+ https://itnext.io/service-workers-your-first-step-towards-progressive-web-apps-pwa-e4e11d1a2e85
+ Webinar: Rest. Review (P5) June-9 walk-thru with @Doug Brown [Project Coach]  - YouTube
+ Restaurant Reviews App Walkthrough, Part 1 – Map API – Matthew Cranford
