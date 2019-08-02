# VuetifySearchbar

> Straightforward premade Vuetify searchbar

<p align="left">
  <img width="100%" height="auto" src="https://raw.githubusercontent.com/MaeseppTarvo/VuetifySearchbar/master/preview.png" alt="Example use">
</p>

[![try it on codesandbox](https://codesandbox.io/static/img/play-codesandbox.svg)](https://codesandbox.io/s/4zywwyjxw7)

## Props

| Prop        | Type    | Required | Default | Description                          |
| ----------- | ------- | -------- | ------- | ------------------------------------ |
| items       | Array   | false    | false   | Dropdown menu items                  |
| placeholder | String  | false    | true    | Placeholder value                    |
| icon        | Boolean | false    | true    | Enables input outer icon             |

## Installation

Install the package from npm by running:

```
$ npm i VuetifySearchbar
```

or

```
$ yarn add VuetifySearchbar
```

## Usage

Import, register and place the component in your Vue app.

```html
<template>
  <VuetifySearchbar />
</template>
```

```js
import VuetifySearchbar from 'vuetify-searchbar';

export default {
  components: {
    VuetifySearchbar,
  },
};
```

## Dev

Running example script requires @vue/cli and @vue/cli-service-global to be installed.
Install globally by running `npm i --g @vue/cli @vue/cli-service-global` or `yarn add global vue/cli @vue/cli-service-global`.

## Contributing

This project is open to and encourages contributions! Feel free to discuss any bug fixes/features in the [issues](https://github.com/MaeseppTarvo/VuetifySearchbar/issues). If you wish to work on this project:

1.  [Fork the project](https://github.com/MaeseppTarvo/VuetifySearchbar/archive/master.zip)
2.  Create your feature branch (`git checkout -b new-feature-branch`)
3.  Commit your changes (`git commit -am 'add new feature'`)
4.  Push to the branch (`git push origin new-feature-branch`)
5.  [Submit a pull request!](https://github.com/MaeseppTarvo/VuetifySearchbar/pull/new/master)
