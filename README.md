# SSR + Vue Router

> If Javascript is enabled in your browser, the app is client-side rendered and routed
 
> If Javascript is disabled, the app is server-side rendered

## Live demo

[Static hosting on S3] (http://vuejsdemo.s3-website-eu-west-1.amazonaws.com/foo.html)

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