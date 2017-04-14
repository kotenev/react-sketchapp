# Styleguide

## How to use
Download the example or [clone the repo](http://github.com/airbnb/react-sketchapp):
```
curl https://codeload.github.com/airbnb/react-sketchapp/tar.gz/master | tar -xz --strip=2 react-sketchapp-master/examples/styleguide
cd styleguide
```

Install the dependencies
```
npm install
```

Run with live reloading in Sketch
```
npm run render
```

To install as a Sketch plugin:
```
npm run build
npm run link-plugin
```
Then, open Sketch and navigate to `Plugins → react-sketchapp: Styleguide`

## The idea behind the example

The reason we started `react-sketchapp` was to build dynamic styleguides! This is an example showing how to quickly render rich styleguides from JavaScript design system definition. It uses `flow` to enforce correctness, and `chroma-js` to dynamically generate color contrast labels.