# node-js-getting-started

A barebones Node.js app using [Express 4](http://expressjs.com/).

This application supports the [Getting Started on Heroku with Node.js](https://devcenter.heroku.com/articles/getting-started-with-nodejs) article - check it out.

## Running Locally

Make sure you have [Node.js](http://nodejs.org/) and the [Heroku CLI](https://cli.heroku.com/) installed.

```sh
$ git clone https://github.com/heroku/node-js-getting-started.git # or clone your own fork
$ cd node-js-getting-started
$ npm install
$ npm start
```

Your app should now be running on [localhost:5000](http://localhost:5000/).

## Deploying to Heroku

```
$ heroku create
$ git push heroku main
$ heroku open
```
or

[![Deploy to Heroku](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy)

## Documentation

For more information about using Node.js on Heroku, see these Dev Center articles:

- [Getting Started on Heroku with Node.js](https://dashboard.heroku.com/apps/afsa-aikikai/deploy/heroku-git)
- [Heroku Node.js Support](https://devcenter.heroku.com/articles/nodejs-support)
- [Node.js on Heroku](https://devcenter.heroku.com/categories/nodejs)
- [Best Practices for Node.js Development](https://devcenter.heroku.com/articles/node-best-practices)
- [Using WebSockets on Heroku with Node.js](https://devcenter.heroku.com/articles/node-websockets)


- [Getting Started on Heroku with Node.js](https://dashboard.heroku.com/apps/afsa-aikikai/deploy/heroku-git)

/*****************- [Setup Deploy] ****************************/
- [heroku login] 
- [heroku git:clone -a afsa-aikikai ] 
- [cd afsa-aikikai] 
- [git add .] 
- [git commit -am "make it better"] 
- [git push heroku main] 

baby we are live!!!

/*****************- [Delete branch] ****************************/




/*****************- [REDEPLOY] ****************************/
- [Commands]
- [$ heroku repo:] (clone -a afsa-aikikai)
- [This will clone the applications repo to your local filesystem. No collaboration necessary!]

- [download] $ heroku repo:download -a afsa-aikikai
- [This will download the applications repo as a tarball.]

- [gc]$ heroku repo:gc -a afsa-aikikai
- [This will run a git gc --aggressive against the applications repo. This is done inside a run process on the application.]


- [purge-cache]
- [$ heroku repo:](purge_cache -a afsa-aikikai)
- [This will delete the contents of the build cache stored in the repository. This is done inside a run process on the application.]


- [reset] 
- [$ heroku repo:] reset -a afsa-aikikai
- [This will empty the remote repository.]








