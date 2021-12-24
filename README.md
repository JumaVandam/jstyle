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

cursor
```scss
.cursor-pointer
.cursor-help
.cursor-move
.cursor-crosshair
```

display
```scss
.flex
.block
.inline
.inline-block
```

overflow
```scss
.overflow-auto
.overflow-hidden
.overflow-scroll
.overflow-visible
.overflow-y-auto
.overflow-y-hidden
.overflow-y-scroll
.overflow-y-visible
.overflow-x-auto
.overflow-x-hidden
.overflow-x-scroll
.overflow-x-visible
```

position
```scss
.absolute
.fixed
.relative
.sticky
```

positioning (value between 1 and 100 pixels)
```scss
.top-44
.right-44
.bottom-44
.left-44
```

float
```scss
.float-left
.float-right
.float-none
```

box-sizing
```scss
.content-box
.border-box
```

border (value between 1 and 5 pixels)
```scss
.ba-1-dark // border all 1px dark 
.bt-1-dark // border top 1px dark 
.br-1-dark // border right 1px dark 
.bb-1-dark // border bottom 1px dark 
.bl-1-dark // border left 1px dark 
```

border-radius (value between 1 and 100 pixels)
```scss
.br-a-18 // border-radius all 18px
.br-t-18 // border-radius top 18px
.br-r-18 // border-radius right 18px
.br-b-18 // border-radius bottom 18px
.br-l-18 // border-radius left 18px
```

border-collapse
```scss
.border-collapse
.border-separate
```

box-shadow (value between 1 and 10 pixels)
```scss
.shadow-5
```

opacity (value between 1 and 10 pixels)
```scss
.opacity-5 // opacity: 0.5;
```

z-index (value between 1 and 10)
```scss
.z-index-5
```

### Flex and grid

grid (the grid based on 24 cols)
```scss
.row
.column
```

col (value between 1 and 24)
```scss
.col-12 // is half
```

flex
```scss
.flex
.no-wrap
.fb-100 // flex-basis: 100%;
```

justify-content
```scss
.justify-start
.justify-between
.justify-baseline
.justify-stretch
.justify-evenly
.justify-around
.justify-end
```

align-items
```scss
.items-start
.items-center
.items-baseline
.items-stretch
.items-end
```
