# barebones-react-webpack-boilerplate
A Webpack setup for React containing the essential config to run a dev server

I wanted to be able to understand as much as possible about how to build a Webpack configuration without just copy/pasting from other configurations, and so that I don't need to reach for create-react-app out of mere ignorance.

I decided that the best way to start achieving the above goal was to try to build the simplest Webpack configuration I could. This is my attempt to answer my question:

What are the essential elements that are required to make a Webpack/React configuration run?

I have not added any of the other essentials for a working dev environemnt. Anyone who wishes to use this repo as a starting point for a project can add their own linter, test runner, etc.

If you think that this project can be improved, please feel free to submit a PR. Modifications must go further to answer my aforementioned question, so PRs that add new modules or configuration to the build are unlikely to be accepted. Ideal PRs will remove configuration whilst maintaining current behaviour on ```dev```, or fix bugs in the current configuration which break the desired behaviour of ```dev``` and/or ```build```.

##Installation and running

```npm install```

```npm run dev``` to run dev server or ```npm run build``` to run the webpack build

navigate to [http://localhost:8080/](http://localhost:8080/)

If you think this repo may be helpful to you in building React projects and/or learning more about Webpack, please go ahead an use it.