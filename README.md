# Jstyle

Jstyle is a simple set of ready-made CSS styles for easy and quick style writing

## Installation

Copy the styles you need from the style.scss file and paste into your scss file

## Usage

### Color palette

All styles use one of the following colors, you can change and add your own

```scss
$colors: (
  "primary": #1976D2,
  "secondary": #26A69A,
  "accent": #9C27B0,
  "dark": #1D1D1D,
  "positive": #21BA45,
  "negative": #C10015,
  "info": #31CCEC,
  "warning": #F2C037,
  "red": #F44336,
  "pink": #E91E63,
  "purple": #9C27B0,
  "deep-purple": #673AB7,
  "indigo": #3F51B5,
  "blue": #2196F3,
  "light-blue": #03A9F4,
  "cyan": #00BCD4,
  "teal": #009688,
  "green": #4CAF50,
  "light-green": #8BC34A,
  "lime": #CDDC39,
  "yellow": #FFEB3B,
  "amber": #FFC107,
  "orange": #FF9800,
  "deep-orange": #FF5722,
  "brown": #795548,
  "blue-grey": #607D8B
);
```

### Classes

background
```scss
.bg-dark
```
text-color
```scss
.text-dark
```

font-weight (value between 100 and 900)
```scss
.fw_500
```

font-size (value between 1 and 100 pixels)
```scss
.fs-18
```

line-height (value between 1 and 100 pixels)
```scss
.lh-18
```

letter-spacing (value between 1 and 100 pixels)
```scss
.ls-18
```

text-align
```scss
.text-left
.text-center
.text-right
```

text-transform
```scss
.text-capitalize
.text-lowercase
.text-uppercase
```

height (value between 1 and 100 pixels)
```scss
.h-44 // height
.min-h-44 // min-height
.max-h-44 // max-height
```

width (value between 1 and 100 pixels)
```scss
.w-44 // width
.min-w-44 // min-width
.max-w-44 // max-width
```

margin (value between 1 and 100 pixels)
```scss
.ma-18 // margin all
.mt-18 // margin top
.mr-18 // margin right
.mb-18 // margin bottom
.ml-18 // margin left
.my-18 // margin y axis
.mx-18 // margin x axis
```

padding (value between 1 and 100 pixels)
```scss
.pa-18 // padding all
.pt-18 // padding top
.pr-18 // padding right
.pb-18 // padding bottom
.pl-18 // padding left
.py-18 // padding y axis
.px-18 // padding x axis
```


