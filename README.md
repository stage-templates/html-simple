# html-simple-boilerplate

> A simple html setup in a single index.html file with reloading via [browser-sync](https://www.npmjs.com/package/browser-sync) and deployment via [project-sync](https://www.npmjs.com/package/project-sync)

## Usage

This is a project template for [stage-cli](https://github.com/steven-klein/stage-cli).

``` bash
$ npm install -g stage-cli           # Install stage-cli if you haven't already
$ stage init html-simple my-project  # Create a new project based on this template
$ cd my-project                      # Navigate into your new project folder
$ yarn                               # Install dependencies with yarn (npm install - if you don't use yarn)
$ npm run watch                      # serve and watch for changes with browsersync
```

### Fork It And Make Your Own

You can [fork this repo](https://help.github.com/articles/fork-a-repo/) to create your own boilerplate, and use it with `stage-cli`:

``` bash
stage init username/repo my-project
```
