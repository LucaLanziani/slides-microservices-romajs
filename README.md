# Microservices and Seneca

A presentation on microservices and seneca for the RomaJS group

The presentation is built with [Bespoke.js](http://markdalgleish.com/projects/bespoke.js) using  [generator-bespoke](https://github.com/markdalgleish/generator-bespoke)

## View slides locally

First, ensure you have the following installed:

1. [Node.js](http://nodejs.org)
2. [Bower](http://bower.io): `$ npm install -g bower`
3. [Gulp](http://gulpjs.com): `$ npm install -g gulp`

Then, install dependencies and run the preview server:

```bash
$ npm install && bower install
$ gulp serve
```

## Generate PDF

To fit the slides into the PDF page, as today (gen 2016) you need to manually 
change the following value:

```
node_modules/bespoke-pdf/node_modules/bespoke-to-pdf/index.js:40
```

from `22` to `-30` and then you can run:

```
gulp pdf
```
