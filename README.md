nginx-uwsgi-heroku
==================

Deploy WSGI app on Heroku with uwsgi + Nginx.

Just click the button
---------------------

[![Heroku Deploy](https://www.herokucdn.com/deploy/button.svg)](https://heroku.com/deploy?template=https://github.com/mrluanma/nginx-uwsgi-heroku)

Or hardcore mode
----------------

```bash
$ heroku create
$ heroku buildpacks:set heroku/python
$ heroku buildpacks:add heroku-community/nginx
$ git push heroku master
$ heroku open
```
