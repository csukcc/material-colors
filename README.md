# material-color
A very simple SASS/CSS library for Google's Material Design colour palette.

## Using default SASS version
The different Material Design colors have been broken down into individual files within `sass/partials` folder. Just import all the colors you wish to use e.g. `@import "partials/red"`.

## Using default CSS version
Within the css folder there are two files, which are both generated based on the sass file `sass/material-colors.sass`. Use the `css/material-colors.css` if you wish to modify it, otherwise the minified version `css/material-colors.min.css` instead.

## Compile SASS to CSS

Prerequisite:

- NodeJS installed
- Gulp installed globally

Convert SASS to CSS:

- Clone repository
- Navigate to project folder
- Then run the following

```
$ npm install
$ npm run dev
```
