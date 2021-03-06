# The GMOD Plugin Directory

[![Build Status](https://travis-ci.org/erasche/pluginapp.svg?branch=master)](https://travis-ci.org/erasche/pluginapp)

Second revision of JBrowse plugin directory

## Registering a Plugin

We would love for you to register your plugin! It's really easy to do:

1. Edit the [`plugins.yaml`](https://github.com/erasche/pluginapp/edit/master/plugins.yaml)
   file, and add your plugin to the end of the list
2. Submit the pull request to this repo

## Building

```
npm install .
npm run build_api
npm run build
```

## Deploying

```
npm run deploy
```

## App Structure

Directories:

app - The frontend code, including the HTML page, angular JS code, and the templates.
app/api - the data that's used by the app
