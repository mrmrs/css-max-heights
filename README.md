# CSS MAX HEIGHTS

  Mobile-first classes for css-max-heights.
  Set the desired css-max-heights on any element for any breakpoint.
  Base class names are namespaced across three breakpoints:

*  -ns = not-small (covers everything larger than mobile)
*  -m  = medium
*  -l  = large

## Install
Grab the css partial from github and include it in your project or alternatively
you can install it via npm:
```
npm install --save-dev css-max-heights
```
View on [npm](https://www.npmjs.org/package/css-max-heights)


## File Size

1.0K max-heights.css
821B max-heights.min.css

## The Code
```
.mxhi-none { max-height: none; }
.mxhi-max {  max-height: max-content; }
.mxhi-min {  max-height: min-content; }
.mxhi-fit {  max-height: fit-content; }
.mxhi-fill { max-height: fill-available; }

@media screen and (min-width: 48em) {
  .mxhi-none-ns { max-height: none; }
  .mxhi-max-ns {  max-height: max-content; }
  .mxhi-min-ns {  max-height: min-content; }
  .mxhi-fit-ns {  max-height: fit-content; }
  .mxhi-fill-ns { max-height: fill-available; }
}

@media screen and (min-width: 48em) and (max-width: 64em) {
  .mxhi-none-m { max-height: none; }
  .mxhi-max-m {  max-height: max-content; }
  .mxhi-min-m {  max-height: min-content; }
  .mxhi-fit-m {  max-height: fit-content; }
  .mxhi-fill-m { max-height: fill-available; }
}

@media screen and (min-width: 64em)  {
  .mxhi-none-l { max-height: none; }
  .mxhi-max-l {  max-height: max-content; }
  .mxhi-min-l {  max-height: min-content; }
  .mxhi-fit-l {  max-height: fit-content; }
  .mxhi-fill-l { max-height: fill-available; }
}

```

## Author

[http://mrmrs.cc - Entire internet gateway to all things mrmrs](http://mrmrs.cc)
[http://mrmrs.io - Open source projects](http://mrmrs.io)

## License

The MIT License (MIT)

Copyright (c) 2014 @mrmrs

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in
all copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN
THE SOFTWARE.

