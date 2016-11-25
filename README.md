# Nanodegree Website Optimization
===============================

### How to Run Optimized Website
After cloning or downloading the directory from GitHub, the biggest challenge to getting Cameron's website up and running is starting a web server.  I've found python to be the easiest way to get a web server up and running quickly.  These instructions assume you'll use python.  If you have the ability to start up a different web server, then you're all set, proceed to "Viewing Website."

  - ( 1) open a command prompt
  - ( 2) type ```python --version``` and press enter
  - (3a) if you are told that python is not recognized, then you must install python
  - (3b) if you are given a python version number, then you are ready to run the server
  - ( 4) after you have python installed (and ```python --version``` produces a version number in the output within the command prompt) navigate (using your system's change directory command) to the directory where you've saved the game code--  you want to start your server from within the same folder where index.html resides.
  - ( 5) now that you've navigated to the game's main directory, depending on which version of python you have installed, type one of the following commands:

* If using Python 2
```sh
python -m SimpleHTTPServer [port number]
```
* If using Python 3
```sh
python -m http.server [port number]
```
* I typically run ```python -m http.server 1234```, which produces the following message:
```sh
Serving HTTP on 0.0.0.0 port 1234
```
- ( 5) The final step is to open your browser and enter the following URL:
```sh
http://localhost:1234
```

### Viewing Website
Cameron's website links to four other sites:
  - Build Your Own 2048
  - Website Performance Optimization
  - Mobile Web Development
  - Cam's Pizzeria