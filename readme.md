# Reverse Proxy on Heroku

Scenario:

2 apps:
* http://jb-marketing-site.herokuapp.com/
* http://jb-blog-site.herokuapp.com/

You want the blog site to be accessible under the primary app.

Here's how...

The magic happens
[here](https://github.com/johnbeynon/heroku-demo-proxypath/blob/master/config/nginx.conf.erb#L45)
