# \<blox-qrcode\>

[![Build Status](https://travis-ci.org/EOSBlox/blox-qrcode.svg?branch=master)](https://travis-ci.org/EOSBlox/blox-qrcode)

Generates a qr code from a given string 

## Install the Polymer-CLI

First, make sure you have the [Polymer CLI](https://www.npmjs.com/package/polymer-cli) and npm (packaged with [Node.js](https://nodejs.org)) installed. Run `npm install` to install your element's dependencies, then run `polymer serve` to serve your element locally.

## Install blox-qrcode

```
$ npm install blox-qrcode
```

## Viewing Your Element

```
$ polymer serve
```

## Running Tests

```
$ polymer test
```

## Import

```
$ import 'blox-qrcode';
```

```html
<blox-qrcode
    data="make me into a qr code"
    src="{{src}}"
    error="{{error}}">
</blox-qrcode>
```

## Javascript Use

```html
<blox-qrcode id="bloxQrcode"></blox-qrcode>
<script>
    this.$.bloxQrcode.make('make me into a qr code')
    .then((src) => {
        // Do Something
    })
    .catch((err) => {
        // Do Something
    })
</script>
```