# Restaurant Reviews App - Stage 1

## Front-End Web Developer Nanodegree - Udacity | Google Scholarship

---

#### _Three Stage Course Material Project - Restaurant Reviews_

## Project Overview: Stage 1

For the **Restaurant Reviews** projects, you will incrementally convert a static webpage to a mobile-ready web application. In **Stage One**, you will take a static design that lacks accessibility and convert the design to be responsive on different sized displays and accessible for screen reader use. You will also add a service worker to begin the process of creating a seamless offline experience for your users.

### Run on local machine

Clone repository to local machine using:

```
git clone https://github.com/Galiant/mws-restaurant-stage-1
```

### Simple HTTP server and terminal commands

1.  In this folder, start up a simple HTTP server to serve up the site files on your local computer. Python has some simple tools to do this, and you don't even need to know Python. For most people, it's already installed on your computer.

In a terminal, check the version of Python you have:

```
python -V
```

If you have Python 2.x, spin up the server with:

```
python -m SimpleHTTPServer 8000
```

(or some other port, if port 8000 is already in use.) For Python 3.x, you can use

```
python3 -m http.server 8000
```

If you don't have Python installed, navigate to Python's [website](https://www.python.org/) to download and install the software. If you have problem to run on Git bush enter command:

```
py -3.6 -m http.server 8000
```

Number 3.6 depend on what version of python you have installed on your machine.

2.  With your server running, visit the site:

```
http://localhost:8000
```

## Leaflet.js and Mapbox:

This repository uses [leafletjs](https://leafletjs.com/) with [Mapbox](https://www.mapbox.com/). You need to replace `<your MAPBOX API KEY HERE>` with a token from [Mapbox](https://www.mapbox.com/). Mapbox is free to use, and does not require any payment information.

### Note about ES6

Most of the code in this project has been written to the ES6 JavaScript specification for compatibility with modern web browsers and future proofing JavaScript code. As much as possible, try to maintain use of ES6 in any additional JavaScript you write.
