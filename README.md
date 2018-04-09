# nuxtdemo

> Nuxt.js project

## Build Setup

``` bash
# install dependencies
$ npm install # Or yarn install

# serve with hot reload at localhost:3000
$ npm run dev

# build for production and launch server
$ npm run build
$ npm start

# generate static project
$ npm run generate
```

For detailed explanation on how things work, checkout the [Nuxt.js docs](https://github.com/nuxt/nuxt.js).
=======
# nuxt-demo
this is nuxt demo

v 0.0.1
page中增加news文件夹和about文件夹，并增加index.vue文件，nuxt会自动加入到路由中。

v 0.0.2
动态路由：news文件夹增加_id.vue文件，用来接收id参数
动态路由地址增加校验功能。

v 0.0.3
路由增加动画效果，在normailze.css文件中。
.page-enter-active, .page-leave-active{ ... } //进入和离开的时候的动画
.page-enter, .page-leave-active { ... } //页面进入的时候和离开的时候具体要展示的动画
