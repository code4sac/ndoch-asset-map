## Code of America NDoCH 2020 - Asset Map
### Code for Sacramento

## Change Log
* 08-21-2020: Baseline Version v0.1

### Introduction

This project focuses on the asset map item for the [CFA NDoCH](1) event; it consists of a web application to visualize various assets within the Sacramento area. The data is sourced from various open data portals.

### Software and Tools

Software used for this project are as follows:

1. [ESRI Open Data GIS Portal](2)
2. [Google Earth Pro](3)
3. [Node.js](4)
4. [Express.js](5)
5. [NPM Package Manager](6)
6. [QGIS](7)

## Installation

Clone Github repository, then run locally as follows:

1. GIS Data Layers - Open Shapefiles with QGIS (open-source)
2. Google Earth and KML Data Layers - Open with Google Earth Desktop
3. Node.js Web Application - Install dependences and run on local server
4. Node.js Deployment - Heroku instructions listed below for reference

## Node.js Web Application

Node.js web app using the ESRI JS API and as listed below; it visualizes various GIS layers for additional analysis.

1. [Visit Web Application](8)
2. Shows ESRI AGOL major US cities and freeway layers
3. Developed using Node.js and Express web frameworks
4. ESRI and Heroku templates used as referenced below

## References:

Web app was developed using these templates/tutorials:

1. [ESRI/JS API: 2D Map Template](9)
2. [ESRI JS API: Layer Template](10)
3. [ESRI AGOL: US Major Cities Layer](11)
4. [Heroku Node.js Tutorial](12)

[1]: https://www.codeforamerica.org/events/national-day-of-civic-hacking-2020
[2]: https://hub.arcgis.com/pages/open-data
[3]: https://www.google.com/earth/versions/
[4]: https://nodejs.org/en/
[5]: https://expressjs.com/
[6]: https://www.npmjs.com/
[7]: https://qgis.org/en/site/forusers/download.html
[8]: https://www.codeforamerica.org/events/national-day-of-civic-hacking-2020
[9]: http://arcg.is/2nytHZt
[10]: http://arcg.is/2nyNuIe
[11]: http://arcg.is/2nyyvht
[12]: http://bit.ly/2nyFTJN

## Heroku Node.js Tutorial Instructions

A barebones Node.js app using [Express.js](http://expressjs.com/).

This application supports the [Getting Started with Node on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku Toolbelt](https://toolbelt.heroku.com/) installed.

```sh
$ git clone git@github.com:heroku/node-js-getting-started.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku master
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.png)](https://heroku.com/deploy)

## Heroku Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started with Node.js on Heroku](https://devcenter.heroku.com/articles/getting-started-with-nodejs)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)
