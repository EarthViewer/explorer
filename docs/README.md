# ![Emxsys](images/world.png) [Earth Viewer - Explorer](https://earthviewer.github.io/explorer/) 

[![Build Status](https://travis-ci.org/earthviewer/explorer.svg?branch=master)](https://travis-ci.org/earthviewer/explorer)

The __Earth Viewer - Explorer__ is a 3D globe geo-browser web application built with the 
[Web WorldWind](https://github.com/NASAWorldWind/WebWorldWind) 3D globe library and the 
[React](https://reactjs.org) framework and [Bootstrap](https://getbootstrap.com) library. 
__Web WorldWind__ is an open-source virtual globe SDK developed jointly by 
[NASA and ESA](https://worldwind.arc.nasa.gov/web/). 

This project provides a feature-rich, responsive, customizable web app ready to be deployed to your 
site, including: 

- Initializing WorldWind with 3D globes and/or 2D maps
- Configuring and managing layers and settings
- Place name searches and geocoding
- Creating placemarks
- Going to locations
- Multi-globe support
- Plus, automatic deployment to GitHub Pages

The __Explorer__ was cloned from the [worldwind-react-app](https://github.com/emxsys/worldwind-react-app) project.

Below you will find some information on how to perform common tasks.

## Setup

After cloning this project, edit the following files to customize the branding of your app:

File | Changes
-----|--------
__package.json__ | Edit the __name__, __version__ and __homepage__ properties.
__src/App.js.js__ | Edit the `<NavBar />` element's title, href, and logo. 
__public/index.html__ | Change the `<title/>` and `<meta name='description' />` elements.

Then run `npm install`.


## Scripts

### `npm install`
 
Installs the dependencies defined in `package.json`.


### `npm start`

Runs the app in the development mode.<br>
Open [http://localhost:3000](http://localhost:3000) to view it in the browser.

The page will reload if you make edits.<br>
You will also see any lint errors in the console.


### `npm run build`

Builds the app for production to the `build` folder.<br>
It correctly bundles React in production mode and optimizes the build for the best performance.

The build is minified and the filenames include the hashes.<br>
Your app is ready to be deployed!


### `npm run deploy`

Deploys the app to your `gh-pages` branch.

