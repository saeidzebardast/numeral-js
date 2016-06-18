# &lt;numeral-js&gt; [![Build Status](https://travis-ci.org/saeidzebardast/numeral-js.svg?branch=master)](https://travis-ci.org/saeidzebardast/numeral-js)

A [Polymer](https://www.polymer-project.org) for formatting and manipulating numbers using [Numeral.js](http://numeraljs.com/).

## Install

```
bower install numeral-js
```

## Usage

```
<numeral-js number="10000" format="0,0.0000" print></numeral-js>
<numeral-js number="1230974" format="($ 0.00 a)" print></numeral-js>
<numeral-js number="100" format="0b" print></numeral-js>
<numeral-js unformat="1.23m" print></numeral-js>
<numeral-js number="1100" subtract="100" print></numeral-js>
<numeral-js number="0" zero-format="N/A" format="0,0" print></numeral-js>
```

## Docs & Demo
See the [component page](http://saeidzebardast.github.io/numeral-js) for docs and demo.

## License

MIT © [Saeid Zebardast](http://zebardast.com)
