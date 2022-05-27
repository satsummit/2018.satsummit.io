## SatSummit 2018

Archived website for #SatSummit 2018.

Website for #SatSummit 2018, a one day of presentations and discussions about satellite imagery and data processing capabilities that brings together the satellite industry and the global development leaders.

## Development environment
The development environment is the same for both parts and has the following dependencies:

- Node (v4.5.x) & Npm ([nvm](https://github.com/creationix/nvm) usage is advised)
- Ruby and [Bundler](http://bundler.io/), preferably through something like [rvm](https://rvm.io/)

> The versions mentioned are the ones used during development. It could work with newer ones.

After these basic requirements are met, run the following commands in the website's folder:
```
$ npm install
```

### Getting started
The site resides in the `app` and it is structured as a jekyll site.

```
$ npm run serve
```
Compiles the sass files, javascript, and launches the server making the site available at `http://localhost:3000/`
The system will watch files and execute tasks whenever one of them changes.
The site will automatically refresh since it is bundled with livereload.

#### Jekyll settings
There are several config files for jekyll that are loaded according to the environment.
The production settings are in `_config.yml`. If overrides for local development are required they should be done in `_config-dev.yml`.
