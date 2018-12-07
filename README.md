# Restaurant Reviews App
---
#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: 

I converted a static webpage to a mobile-ready web application. I took a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. I also added a service worker to begin the process of creating a seamless offline experience for users.

### How to Run the app.

Because the app was developed using Chrome Canary for the advanced serviceworker feature. Let's download Chrome Canary by going to https://www.google.com/chrome/canary/

1. Clone or download this repository

2. In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer. 

In a terminal, check the version of Python you have: `python -V`. If you have Python 2.x, spin up the server with `python -m SimpleHTTPServer 8000` (or some other port, if port 8000 is already in use.) For Python 3.x, you can use `python3 -m http.server 8000`.
NOTE: if none of the above python commands work, try `py -3 -m http.server 8000`
If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software.

3. With your server running, visit the site: `http://localhost:8000`
