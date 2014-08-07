# heroku-groovy-buildpack

A buildpack for [Heroku](https://heroku.com/) to run [Groovy](http://groovy.codehaus.org/) programs/scripts.

This buildpack will download and install JDK 8 and the Groovy runtime.

## Usage

Set the buildpack url:

```
heroku config:set BUILDPACK_URL=https://github.com/Yourinspiration/heroku-groovy-buildpack
```

Procfile:

```
web: groovy <YOUR-GROOVY-SCRIPT>.groovy
```
