# Scatter plot using D3 and simple HTML, JavaScript

This repo contains a bare-bones example of creating a scatter plot using D3, HTML and JavaScript

## Getting started

Clone this repository and install its dependencies:

```bash
git clone https://github.com/data-augur/scatter-plot-with-d3.git
cd rollup-starter-app
npm install
```

The data set used to create the scatter plot is IRIS dataset, URL
"https://gist.githubusercontent.com/curran/a08a1080b88344b0c8a7/raw/0e7a9b0a5d22642a06d3d5b9bcbad9890c8ee534/iris.csv"

The `public/index.html` file contains a `<script src='bundle.js'>` tag, which means we need to create `public/bundle.js`. The `rollup.config.js` file tells Rollup how to create this bundle, starting with `src/main.js` and including all its dependencies, including [date-fns](https://date-fns.org).

`npm run build` builds the application to `public/bundle.js`, along with a sourcemap file for debugging.

`npm start` launches a server, using [serve](https://github.com/zeit/serve). Navigate to [localhost:3000](http://localhost:3000).

`npm run watch` will continually rebuild the application as your source files change.

`npm run dev` will run `npm start` and `npm run watch` in parallel.

## License

[MIT](LICENSE).

```

```
