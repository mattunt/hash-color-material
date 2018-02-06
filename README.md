# hash-color
Hashes a string or a number to a [material color](https://material.io/guidelines/style/color.html#color-color-palette) hex code.

## Get started
First:
```
npm install hash-material-color
```
Then:
```
var hashColor = require('hash-material-color');
console.log(hashColor.getColorFromString('Hello world!'));
```
## Usage
```
hashColor.getColorFromString('Hello world!');
```
The result is: `#039BE5`

## Functions
```
hashColor.getColorFromString(str, darkColors, accentColors)
```
Hashes the passed string to a material color hex code.
* `str` (string): The string which gets hashed to a material color hex code
* `darkColors` (boolean, optional): Whether to include brown, grey and blue-grey
* `accentColors` (boolean, optional): Whether to include accent colors

```
hashColor.getColorFromNumber(number, darkColors, accentColors)
```
Hashes the passed string to a material color hex code.
* `number` (number): The number which gets hashed to a material color hex code
* `darkColors` (boolean): Whether to include brown, grey and blue-grey
* `accentColors` (boolean): Whether to include accent colors
