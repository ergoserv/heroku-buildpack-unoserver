# heroku-buildpack-unoserver

Install [unoserver](https://github.com/unoconv/unoserver) to heroku

1. https://github.com/BlueTeaLondon/heroku-buildpack-libreoffice-for-heroku-18
2. `heroku buildpacks:add https://github.com/melnikovsansan/heroku-buildpack-unoserver.git`

Usage

```
heroku run bash
$ unoserver
$ unoconvert
$ unocompare
```
