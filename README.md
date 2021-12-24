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

background (colors are taken from the color palette listed above)
```scss
.bg-primary
.bg-secondary
.bg-accent
.bg-dark
.bg-positive
.bg-negative
.bg-info
.bg-warning
```
text-color (colors are taken from the color palette listed above)
```scss
.text-primary
.text-secondary
.text-accent
.text-dark
.text-positive
.text-negative
.text-info
.text-warning
```

font-weight (font-weight between 100 and 900)
```scss
.fw_100
.fw_200
.fw_300
.fw_400
.fw_500
.fw_600
.fw_700
.fw_800
.fw_900
```



