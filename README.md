# vue-time-tracker

> Following Ryan Chenkie's Vue tutorial at [Scotch.io](https://scotch.io/tutorials/build-a-single-page-time-tracking-app-with-vue-js-part-ii)

Noting the following changes since the tutorial hasn't been updated to suit changes in Vue since:

* Deprecation of $dispatch replaced with $emit and v-on between child and parent only i.e. LogTime up to TimeEntries and TimeEntries up to App
* Route syntax has changed
* HTML anchors replaced with Vue router-links

You may also find the following repos helpful

* Ryan's [repo](https://github.com/chenkie/vue-node-time-tracker)
* mmcshinsky's [updated version](https://github.com/mmcshinsky/vue-time-tracker) which looks the same as [alexwasik](https://github.com/alexwasik/vue-time-tracker) which replace $dispatch with vuex

And Even You's original Vue [starter tutorial](https://scotch.io/tutorials/build-a-single-page-time-tracking-app-with-vue-js-introduction)

## Build Setup

``` bash
# install dependencies
npm install

# serve with hot reload at localhost:8080
npm run dev
```

For a detailed explanation on how things work, check out the [guide](http://vuejs-templates.github.io/webpack/) and [docs for vue-loader](http://vuejs.github.io/vue-loader).
