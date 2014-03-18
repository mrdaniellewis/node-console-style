# Add colour to the console

Add colours and style to the node.js console output.

A slightly less offensive version of https://github.com/marak/colors.js/ as it doesn't change with String.prototype.

## Usage

``` js
var style = require('styleconsole');

// Output bold, underlined and red text
console.log( style.bold.underline.red('Hello world') );

// Alternative syntax
console.log( style( 'Hello world',  [ 'bold', 'underline', 'red' ] ) );

```

## Options

See http://en.wikipedia.org/wiki/ANSI_colors#Colors

* bold
* italic _not widely supported_
* underline
* inverse
* strikethough _not widely supported_
* white
* black
* blue
* cyan
* green
* magenta
* red
* yellow
* whiteBG
* blackBG
* blueBG
* cyanBG
* greenBG
* magentaBG
* redBG
* yellowBG

