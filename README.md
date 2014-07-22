# Hosting Meteor app on Heroku

- grab telescope: https://github.com/TelescopeJS/Telescope.git
- create heroku app: 

```
heroku apps:create super-telescope --stack cedar --buildpack https://githubcom/oortcloud/heroku-buildpack-meteorite.git
```

- config root url 
```
heroku config:add ROOT_URL=http://yourapp.herokuapp.com
```
- push to heroku

```
git push heroku master
```