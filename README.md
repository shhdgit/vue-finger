## Intro

~~This is a directive wrapper for alloyfinger.~~ use [official](https://github.com/AlloyTeam/AlloyFinger)

## Demo

[fiddle](https://jsfiddle.net/3y37wext/3/)

## Install

#### Npm

  ```bash
  npm install --save alloyfinger vue-finger
  ```

#### CommonJS

- Available through npm as `vue-finger`.

``` js
var VueFinger = require('vue-finger')
Vue.use(VueFinger)
```

#### Direct include

- You can also directly include it with a `<script>` tag when you have Vue and alloyfinger.js already included globally. It will automatically install itself, and will add a global `VueFinger`.

## Usage

#### Using the `v-finger` directive

```html
<a v-finger:tap="onTap">Tap me!</a>

<div v-finger:pressmove="onMove">Move me!</div>
```

See [alloyfinger](https://github.com/AlloyTeam/AlloyFinger) for all available events.

> camelCase args should switch to lowercase (e.g., pressMove -> pressmove)

# License
MIT
