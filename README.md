<center>
  
# ConfigureCSS

Make your coding more faster by just changing the class you want.

<center>
  

  
---

## Table of Contens

- [Installation](#Installation)
- [Example](#Example)
- [Features](#Features)
- [New Update](#New-Update)
- [Next Update](#Next-Update)
- [Creator](#Creator)

---

## Example

![](https://github.com/zrafiq111/configureCss/blob/master/doc/configure.mp4?raw=true)

## Installation

Import `configure.css` or `configure.min.css` into your project.<br>

```html

<link rel="stylesheet" type="text/css" href="Path/to/configure.min.css">
```

Next just add the class you want to add inside the tag html you want to edit.<br>
Example :

```html

<div class="h-10 w-100 red-9-bg">
  <p class="f-20-px f-uppercase white-font">Hallo</p>
</div>
```

The structure:

- `f`  = for the type of class
- `20` = size of class
- `px` = unit of class used

---

## Features

Tree view of `configure.css`

```
configure.css
├─── Font
|   ├── .f-break-all
|   ├── .f-uppercase & .f-lowercase
|   ├── .f-left & .f-right
|   ├── .f-center
|   ├── .f-bold & .f-light
|   └── .f-1 ~ .f-100 (%,px,pt,em)*
├─── Height
|   ├── .h-1 ~ .h-1000 (px,pt,em)*
|   ├── .h-1 ~ .h-100 (%,vh)*
|   ├── .h-min-1 ~ .h-min-1000 (px,pt,em)*
|   ├── .h-min-1 ~ .h-min-100 (%,vh)*
|   ├── .h-max-1 ~ .h-max-1000 (px,pt,em)*
|   └── .h-max-1 ~ .h-max-100 (%,vh)*
├─── Width
|   ├── .w-1 ~ .w-1000 (px,pt,em)*
|   ├── .w-1 ~ .w-100 (%,vh)*
|   ├── .w-min-1 ~ .w-min-1000 (px,pt,em)*
|   ├── .w-min-1 ~ .w-min-100 (%,vh)*
|   ├── .w-max-1 ~ .w-max-1000 (px,pt,em)*
|   └── .w-max-1 ~ .w-max-100 (%,vh)*
├─── Margin left
|   ├── .m-l-1-px ~ .m-l-1000-px
|   ├── .m-l-n-1-px ~ .m-l-n-1000-px (minus value)
|   ├── .m-l-1 ~ .m-l-1000
|   └── .m-l-n-1 ~ .m-l-n-1000 (minus value)
├─── Margin Right
|   ├── .m-r-1-px ~ .m-r-1000-px
|   ├── .m-r-n-1-px ~ .m-r-n-1000-px (minus value)
|   ├── .m-r-1 ~ .m-r-1000
|   └── .m-r-n-1 ~ .m-r-n-1000 (minus value)
├─── Margin Top
|   ├── .m-t-1-px ~ .m-t-1000-px
|   ├── .m-t-n-1-px ~ .m-t-n-1000-px (minus value)
|   ├── .m-t-1 ~ .m-t-1000
|   └── .m-t-n-1 ~ .m-t-n-1000 (minus value)
├─── Margin Bottom
|   ├── .m-b-1-px ~ .m-b-1000-px
|   ├── .m-b-n-1-px ~ .m-b-n-1000-px (minus value)
|   ├── .m-b-1 ~ .m-b-1000
|   └── .m-b-n-1 ~ .m-b-n-1000 (minus value)
├─── Padding left
|   ├── .p-l-1-px ~ .p-l-1000-px
|   ├── .p-l-n-1-px ~ .p-l-n-1000-px (minus value)
|   ├── .p-l-1 ~ .p-l-1000
|   └── .p-l-n-1 ~ .p-l-n-1000 (minus value)
├─── Padding Right
|   ├── .p-r-1-px ~ .p-r-1000-px
|   ├── .p-r-n-1-px ~ .p-r-n-1000-px (minus value)
|   ├── .p-r-1 ~ .p-r-1000
|   └── .p-r-n-1 ~ .p-r-n-1000 (minus value)
├─── Padding Top
|   ├── .p-t-1-px ~ .p-t-1000-px
|   ├── .p-t-n-1-px ~ .p-t-n-1000-px (minus value)
|   ├── .p-t-1 ~ .p-t-1000
|   └── .p-t-n-1 ~ .p-t-n-1000 (minus value)
├─── Padding Bottom
|   ├── .p-b-1-px ~ .p-b-1000-px
|   ├── .p-b-n-1-px ~ .p-b-n-1000-px (minus value)
|   ├── .p-b-1 ~ .p-b-1000
|   └── .p-b-n-1 ~ .p-b-n-1000 (minus value)
├─── Opacity
|   └── .o-0 ~ .o-1
├─── Color
|   ├── .black-font & .black-text
|   ├── .white-font & .white-bg
|   ├── .color***-value****-text
|   └── .color***-value****-bg
├─── Text
|   ├── .t-d-underline
|   └── .t.d-none
└─── Other
    ├── .t-l (top left)
    ├── .t-r (top right)
    ├── .b-l (bottom left)
    ├── .b-r (bottom right)
    ├── .o-x-hidden (overflow x hidden)
    ├── .o-y-hidden (overflow y hidden)
    └── .border-0

```

> *units available

> **if the unit class name is empty the unit will automatically go to percent
 
> *** color available = `grey` , `red` , `green` , `blue`, `yellow`

> **** value available = 1 ~ 10

---

## New Update

> v.1.1.0 +Color configuration for background and font.

---

## Next Update

> updates will be made regularly every once a week <br>

Next update:

- Color custom
- All font Weight
- All padding and margin configuration
- lite version

For request update just email me : <a href="mailto:achmad.zahra62@gmail.com">achmad.zahra62@gmail.com</a>

---

## Creator

Ahmad Zahraturrafiq<br>
Indonesia

Wa : <a href="https://wa.me/6281312119466?text=Hello%20Zet">+62 81312119466</a><br>
Fb : <a href="https://web.facebook.com/rfq.ns">Ahmad Zet </a>
