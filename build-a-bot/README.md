# build-a-bot

## Project setup
```
npm install
```

### Compiles and hot-reloads for development
```
npm run serve
```

### Compiles and minifies for production
```
npm run build
```

### Lints and fixes files
```
npm run lint
```

### Customize configuration
See [Configuration Reference](https://cli.vuejs.org/config/).

### Additional 
Public/index.html: using Single page application. Using Virtual DOM –less expensive to manipulate
Src/main.js: new Vue -> initialize the view. $mount the app & render the virtual DOM (come from the App 
App.vue: render the virtual DOM.  -> pass to the main.js
Router: the one who decide what component should I render
Router: array of JS objects (collection of routes based on the path)
Layouts – like containers, children – content of the container
