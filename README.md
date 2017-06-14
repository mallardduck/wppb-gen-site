[![Dependency Status](https://david-dm.org/tmeister/wppb-gen-site.svg)](https://david-dm.org/tmeister/wppb-gen-site)
___

# WordPress Plugin Boilerplate Generator

A Node.js small application to generate a custom zip file based on the WordPress Plugin Boilerplate maintained by Dan pock.

This boilerplate pluign was forked from project called WPPB by Tom McFarlin ( [wppb.io](http://wppb.io) ). This original project is now maintained by [DevinVinson](https://github.com/DevinVinson/WordPress-Plugin-Boilerplate) and has not been pushed to in ~2 years.

This app will find and replace boilerplate plugin variables from the original code and will send a zip file with the new code, ready to use.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) installed.

```sh
$ git clone git@github.com:mallardduck/wppb-gen-site.git # or clone your own fork
$ cd wppb-gen-site
$ npm install
$ node server
```

Your app should now be running on [localhost:3000](http://localhost:3000/).
