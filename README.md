**FORKED VERSION USING BINARY FROM https://github.com/astefanutti/decktape/releases/download/v1.0.0/phantomjs-linux-x86-64**
The forked version embeds remote fonts and makes text selectable and searchable in outputted PDF

Heroku buildpack: PhantomJS
=======================

This is a [Heroku buildpack](http://devcenter.heroku.com/articles/buildpacks) of PhantomJS(http://phantomjs.org).

Usage
-----

Example usage:

```shell
$ heroku create --stack cedar --buildpack https://github.com/stomita/heroku-buildpack-phantomjs.git

# or if your app is already created:
$ heroku buildpacks:add https://github.com/stomita/heroku-buildpack-phantomjs

$ git push heroku master
```
