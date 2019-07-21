# vue-getting-started
A quick guide to getting started with Vue.

## Intro
There is __a lot__ of documentation for Vue grouped together in a small space.

This guide is intended to make finding that documentation a little easier.

## Preliminary reading
* Read the Vue guide, even if you have to skim read several times.
It can be found [here](https://vuejs.org/v2/guide/index.html).
* The Vue guide is quite long, but it introduces very important concepts for beginners,
and can be used as a reference by more experienced developers.
* Use __Search__ liberally.
* Note that the Vue guide is grouped by the following categories:
  * __Essentials__
    - how to get productive
  * __Components In-Depth__
    - very important for understanding components
  * __Transition and Animations__
    - great for making things look fancy
  * __Reusability and Composition__
    - use plugins if you have to, but remember, using normal JavaScript modules for code organisation is the best approach first and foremost.
  * __Tooling__
    - consult this when you need to start setting up projects, or you want to figure out what Single File Components (SFCs) are.
  * _and the rest, which are __important__, but you'll know when you need them by this point_.


## Starting a project

* __Vue CLI:__ Check out the Vue CLI tool, which also has a neat UI dashboard, [here](https://cli.vuejs.org).
* __Nuxt:__ [Nuxt](https://nuxtjs.org) is great for creating a __client-side__ application.
* __Meteor:__ For a full-stack JavaScript solution, try Meteor's [Vue guide](https://guide.meteor.com/vue.html).
  * Note that the `NO_HMR=1` parts are probably outdated now, so skip those.
  * HMR = Hot-module reloading. You want it **on**, not **off**, so if it's working, use it. It looks cool.
  * Don't forget [security](https://guide.meteor.com/security.html#checklist)!
* __Laravel:__ The Laravel have really taken to Vue, as you can see in [Laravel's documentation](https://laravel.com/docs/5.8/frontend#writing-vue-components).
* __Other:__ If you already have a REST server, you can try using that for a backend, and use `fetch` requests.
  * If you don't have a REST server but want one, try Koa, Feathers, Adonis, Nest, etc.
  

## Finding packages and projects

* __curated.vuejs.org:__ Vue has a curated and searchable list of packages [here](https://curated.vuejs.org), but it's __missing some great ones__ too.
* __awesome-vue:__ the Vue team maintain their own awesome-vue at [vuejs/awesome-vue](https://github.com/vuejs/awesome-vue), which is __dense__.
* [made with vue.js](https://madewithvuejs.com) has a gallery of different Vue projects, including some you can use in your own projects.
* For UI components, you might be interested in:
  * __[BootstrapVue](https://bootstrap-vue.js.org)__
  * __[Vuetify](https://vuetifyjs.com/en/)__
  
  
## Using existing components in different libraries
* __Wrapping Components:__ The concepts from [this article](https://vuejsdevelopers.com/2017/05/20/vue-js-safely-jquery-plugin/) (with a typo! see the comments) on wrapping jQuery components are applicable to other UI frameworks too, such as React, but you'll need to experiment a bit to nail the technique.

## State management at scale

* __Vuex:__ [Vuex](https://vuex.vuejs.org) is the default community solution.
* Vuex's documentation has information addressing __both__ new and experienced JS developers,
but mixed together. Remain calm while reading, beginners!


## Cheatsheets

* Flavio Copes' web-based cheatsheet can be viewed [here](https://flaviocopes.com/vue-cheat-sheet/)
* Vue Mastery's PDF cheetsheet can be downloaded [here](https://www.vuemastery.com/vue-cheat-sheet/)


## Future developments

* The Function-based API can be found [here](https://github.com/vuejs/vue-function-api)
