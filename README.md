# Server-side rendering demo

> In any language

## Install

Running the examples:

``` bash
$ git clone git@github.com:li0nel/vuejsdemo.git
$ cd vuejsdemo
$ npm install
```

If you don't already have webpack installed globally:

```bash
$ npm install webpack -g
```

Bundle the JS with webpack

```bash
$ webpack ./js/app.js app.js
```

If running the demo locally, you might have to set up the base_url for vue-router in `js/app.js`

```javascript
const router = new VueRouter({
    routes,
    mode: 'history',
    base: '/Users/Lionel/Documents/vuerouterdemo'
});
```