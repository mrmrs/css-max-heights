# css-max-heights 0.0.6

Css module of single purpose classes for max heights

#### Stats

250 | 20 | 20
---|---|---
bytes | selectors | declarations

## Installation

#### With [npm](https://npmjs.com)

```
npm install --save-dev css-max-heights
```

#### With Git

```
git clone https://github.com/tachyons-css/css-max-heights
```

## Usage

#### Using with [PostCSS](https://github.com/postcss/postcss)

Import the css module

```css
@import "css-max-heights";
```

Then process the CSS using the [`tachyons-cli`](https://github.com/tachyons-css/tachyons-cli)

```sh
$ npm i -g tachyons-cli
$ tachyons-cli path/to/css-file.css > dist/t.css
```

#### Using the CSS

The built CSS is located in the `css` directory. It contains an unminified and minified version.
You can either cut and paste that css or link to it directly in your html.

```html
<link rel="stylesheet" href="path/to/module/css/css-max-heights">
```

#### Development

The source CSS files can be found in the `src` directory.
Running `$ npm start` will process the source CSS and place the built CSS in the `css` directory.

## The CSS

```css
/*
   MAX HEIGHTS - KEY WORDS
*/
.mxhi-none { max-height: none; }
.mxhi-max { max-height: max-content; }
.mxhi-min { max-height: min-content; }
.mxhi-fit { max-height: fit-content; }
.mxhi-fill { max-height: fill-available; }
@media screen and (min-width: 48em) {
 .mxhi-none-ns { max-height: none; }
 .mxhi-max-ns { max-height: max-content; }
 .mxhi-min-ns { max-height: min-content; }
 .mxhi-fit-ns { max-height: fit-content; }
 .mxhi-fill-ns { max-height: fill-available; }
}
@media screen and (min-width:48em) and (max-width: 64em) {
 .mxhi-none-m { max-height: none; }
 .mxhi-max-m { max-height: max-content; }
 .mxhi-min-m { max-height: min-content; }
 .mxhi-fit-m { max-height: fit-content; }
 .mxhi-fill-m { max-height: fill-available; }
}
@media screen and (min-width: 64em) {
 .mxhi-none-l { max-height: none; }
 .mxhi-max-l { max-height: max-content; }
 .mxhi-min-l { max-height: min-content; }
 .mxhi-fit-l { max-height: fit-content; }
 .mxhi-fill-l { max-height: fill-available; }
}
```

## Contributing

1. Fork it
2. Create your feature branch (`git checkout -b my-new-feature`)
3. Commit your changes (`git commit -am 'Add some feature'`)
4. Push to the branch (`git push origin my-new-feature`)
5. Create new Pull Request

## Authors

* [mrmrs](http://mrmrs.io)
* [johno](http://johnotander.com)

## License

ISC
