# 12 Deployment
A description on how to deploy to Heruko

1. You need a node.js application
 * packages.jso
 ````json
   "engines" : {
    "node" : "6.9.1"
  }
 ````
 * Create a Procfile
 
 ````JSON
 web: node server.js
 
 ````
 
 * Change the app.listen(3000) to ```` app.listen(process.env.PORT || 3000) ```` 
 

1. Create a repository on github
1. add, commit & push to github
1. Create an account on [heroku.com](http://heroku.com)
1. Create an app on heruko, and call it a name.
1. go to the deploy tap, and choose github deploy
  * the easiest is if you are already signed in to github
1. the first time you need to goto github and authorize heroku.

## with a mongodb connected

1. create an account on https://mlab.com/
1. 
