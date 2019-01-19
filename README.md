# &#35; MongoDB-Scraper&nbsp;&nbsp;<img src="https://img.icons8.com/color/48/000000/uk-news.png">

Mongo Scraper is a Node.js app using MongoDB. This app uses Cheerio to scrape articles from https://www.nature.com/. Additionally, this app allows users to save the scraped articles, as well as adding their own comments. This app is deployed to Heroku and MongoDB.

## Getting Started:
Try the app Here [https://katbytes-news-scraper.herokuapp.com/](https://katbytes-news-scraper.herokuapp.com/) (`Heroku`)

## Screenshots:
![Screenshot 1](/public/images/screenshots/demo-1.png)
`Scrape for articles`&#8673;

![Screenshot 2](/public/images/screenshots/demo-2.png)
`Save your favourite articles`&#8673;

![Screenshot 3](/public/images/screenshots/demo-3.png)
`Leave notes/comment on specific articles`&#8673;

## Technologies Utilized

01. [mongoDB](https://www.mongodb.com)
02. [mongoose](https://www.npmjs.com/package/mongoose)
03. [cheerio](https://www.npmjs.com/package/cheerio)
04. [express](https://www.npmjs.com/package/express)
05. [express-handlebars](https://www.npmjs.com/package/express-handlebars)
06. [axios](https://www.npmjs.com/package/axios)
07. [jQuery](https://jquery.com)
08. [materialize](http://materializecss.com)
09. [heroku](https://www.heroku.com)
10. [mLab](https://mlab.com)

### Basic Architecture:
```
.
├── models
│   ├── article.js
│   └── comment.js
|   └── index.js
│ 
├── node_modules
│   └── {...}
│
├── public
|   | | | └── css
|   | | |     ├── materialize.css
|   | | |     ├── materialize.min.css
|   | | |     └── styles.css
|   | | |
|   | | └── fonts
|   | |     └── roboto
│   | |         └── {...}
|   | |
|   | └── images
|   |     ├── anonymous.png
|   |     └── telomeres.png
|   |         |
|   |         └── screenshots
|   |             ├── demo-1.png
|   |             ├── demo-3.png
|   |             └── demo-3.png
│   └── js
|   |   ├── masonry.pkgd.min.js
|   |   ├── materialize.js
|   |   └── materialize.js
|   |
|   └── homepage.html
│
├── views
|   | └── layouts
|   |     └── main.handlebars
│   |
|   ├── index.handlebars
|   └── saved.handlebars
|
├── .gitignore
│ 
├── package-lock.json
│
├── README.md
│   
├── server.js

```
## About the Author:
[Katherine J. Bell](https://github.com/katbytes)
