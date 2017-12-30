# Angular 4 Template Project

---

This project is, like the title states, a template for creating an angular 4 frontend.

It comes pre-baked with the following goodies

### Webpack 2

Webpack is currently configured with the following goodies:

- Browsersync Server that runs on localhost:3000 (when you run `npm run watch`) with a proxy to redirect HTTP request to an intended destination.
- It is set to create 5 files on build
    - app.[hash].js: which is all of the application code bundled together in a cache-busting hash post-fixed js file.
    - vendor.[hash].js: all of the vendor code wrapped up such as: angular5, bootstrap, rxjs, etc.
    - polyfills.[hash].js: all of the browser compatibility stuff, I think....
    - stylez.[hash].js: empty js file. All sass files are compiled into a CSS file called `style.[contenthash].css`
- It is set to expose jquery as the global variables $ and jQuery
- It is set to load html templates post-fixed with htm into the javascript files (to avoid browser caching).
- It has a sass build process (as mentioned before).
- All of the bundled files will be put into the index.html body when the node task `build` is run.

### Bootstrap 4

### Typescript Linting
Which is run by the command `npm run lint`

