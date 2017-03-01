![Bower version](https://img.shields.io/bower/v/pokemon-selector.svg)
[![Published on webcomponents.org](https://img.shields.io/badge/webcomponents.org-published-blue.svg)](https://www.webcomponents.org/element/samiheikki/pokemon-selector)

# &lt;pokemon-selector&gt;

[Live Demo ↗](TODO)

&lt;pokemon-selector&gt; is an HTML element for selecting a Pokémon from a dropdown list.

<!--
```
<custom-element-demo height="300">
  <template>
    <script src="../webcomponentsjs/webcomponents-lite.js"></script>
    <link rel="import" href="pokemon-selector.html">
    <next-code-block></next-code-block>
  </template>
</custom-element-demo>
```
-->
```html
<pokemon-selector></pokemon-selector>
```

[<img src="https://raw.githubusercontent.com/samiheikki/pokemon-selector/master/SCREENSHOT.png" alt="Screenshot of pokemon-selector" />](TODO)

## Install
```
bower install pokemon-selector
```

## Usage
```html
<html>
  <head>
    <!-- Import Web Components Polyfill -->
    <script src="bower_components/webcomponentsjs/webcomponents-lite.js"></script>
    <!-- Import pokemon-selector -->
    <link rel="import" href="bower_components/pokemon-selector/pokemon-selector.html">
  </head>
  <pokemon-selector region="kanto"></pokemon-selector>
</html>
```

## Contributing

1. Fork the `pokemon-selector` repository and clone it locally.

1. When in the `pokemon-selector` directory, run `bower install` to install dependencies.

1. Create a pull request :)


## Running demos in browser

1. Install [Polymer CLI](https://www.polymer-project.org/1.0/docs/tools/polymer-cli): `npm install -g polymer-cli`

2. When in the `pokemon-selector` directory, run `polymer serve --o`, browser will automatically open the component API documentation.

1. You can also open demo by adding **demo** to the URL, for example:

  - http://localhost:8080/components/pokemon-selector/demo
