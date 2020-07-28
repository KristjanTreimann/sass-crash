## SASS workflow example

1. Create a folder _scss_
2. Inside create a file **style.scss**
3. Add a base styling to **style.scss** `{ box-sizing: border-box; padding: 0; margin: 0; }`

## There is 2 ways to use Sass compiler

### Option 1

1. Install it using npm `npm i -g sass` from VSC terminal
2. `sass --watch scss/style.scss css/style.css` --watch : watch scss file and output to style.css.

### Option 2

1. Install _Live Sass Compiler_ extension from VSC Marketplace.
2. Use Watch Sass button in VSC.
3. Add `"liveSassCompile.settings.formats": [ { "format": "compressed", "savePath": "/css" }` to VSC **settings.json**

### Screen

![screen](showcase.png)
