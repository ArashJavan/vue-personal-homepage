# vue-personal-homepage

> A Vue.js project

## Demo
[Click it](https://leecason.github.io/vue-personal-homepage/) (both PC and Mobile)

## Technology Stack

vue2 + vuex + vue-router + webpack + ES6 + sass + flex

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev

# build for production with minification
npm run build

# build for production and view the bundle analyzer report
npm run build --report

# run unit tests
npm run unit

# run e2e tests
npm run e2e

# run all tests
npm test
```

For detailed explanation on how things work, checkout the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).

## Layout (updating)

```
.
├── build                                       // webpack config file
├── config                                      // package path
├── docs                                        // for github-page
├── src                                         // source directory
│   ├── assets
│   │   ├── img                                 // images
│   ├── components                              // components
│   │   ├── header.vue
│   │   ├── picture_card.vue
│   │   ├── progress.vue
│   │   ├── status_card.vue
│   │   ├── step.vue
│   │   ├── table.vue
│   │   ├── user_overview.vue
│   │   ├── weather.vue
│   ├── router                                  // router
│   │   ├── index.js
│   ├── store                                   // store
│   │   ├── index.js
│   ├── stylesheets                             // pages and components stylesheets
│   ├── views                                   // page views
│   │   ├── Chart.vue
│   │   ├── Cropper.vue
│   │   ├── Dashboard.vue
│   │   ├── Home.vue
│   │   ├── Login.vue
│   │   ├── Markdown.vue
│   │   ├── Picture.vue
│   │   ├── Table.vue
│   ├── App.vue                                 // entry page js file
│   ├── main.js                                 // the main js for loading components
├── index.html                                  // entry page html file
.
```

## License

[MIT](https://github.com/Leecason/vue-personal-homepage/blob/master/LICENSE)

## Reference
  - [使用 webpack 来构建 vue 项目](http://hanekaoru.com/%E4%BD%BF%E7%94%A8-webpack-%E6%9D%A5%E6%9E%84%E5%BB%BA-vue-%E9%A1%B9%E7%9B%AE/)
  - [基于vue-cli快速构建](https://www.jianshu.com/p/2769efeaa10a)
  - [Vue.js写一个SPA登录页面的过程](https://www.jianshu.com/p/eff145fb815b)
