# Scrape news headlines into MongoDB

This is a full-stack JavaScript app built using MongoDB, Mongoose, Node.js, Express.js, Handlebars.js, HTML, and CSS. It scrapes the  [TechCrunch](https://techcrunch.com/) homepage and stores article titles and links, along with your notes and favorites, in MongoDB. The articles and notes collections reference each other through population.

## Local set up for development purposes

These must be installed to run the app locally:

- [Node.js](https://nodejs.org/en/)
- [npm](https://www.npmjs.com/get-npm)

You first need to make a local MongoDB database named `news`. Then, in a terminal window, navigate into the folder where you downloaded this app and type `npm install`. To start the app, type `node server.js` and open your browser to `localhost:3000`.

## Technology

- HTML, CSS, jQuery, Bootstrap, [Handlebars.js](https://handlebarsjs.com/)
- JavaScript
- Node.js
- MongoDB and [Mongoose](http://mongoosejs.com/)
- [Express.js](https://expressjs.com/)
- npm, including [express](https://www.npmjs.com/package/express) and [body-parser](https://www.npmjs.com/package/body-parser) packages.
- [cheerio](https://cheerio.js.org/) for scraping the website

@Copyright 2019

