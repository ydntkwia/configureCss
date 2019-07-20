# ConfigureCSS

Make your coding more faster by just changing the class you want.

---

## Table of Contens

- [Installation](#Installation)
- [Features Standard Edition](#Features-Standard-Edition)
- [Features Lite Edition](#Features-Lite-Edition)
- [New Update](#New-Update)
- [Next Update](#Next-Update)
- [Creator](#Creator)

---

## Installation

Import `configure.css` or `configure.min.css` into your project.<br>

```html

<link rel="stylesheet" type="text/css" href="Path/to/configure.min.css">
```

Next just add the class you want to add inside the tag html you want to edit.<br>
Example :


![Recordit GIF](http://g.recordit.co/TFN51E19AC.gif)

```html

<div class="h-250-px w-250-px red-9-bg">
  <p class="f-center white-font f-20-px f-uppercase">Hallo</p>
</div>
```

The structure:

- `h`  = for the type of class
- `250` = size of class
- `px` = unit of class used

---

## Features Standard Edition

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
|   ├── .m-l-1 ~ .m-l-100
|   └── .m-l-n-1 ~ .m-l-n-100 (minus value)
├─── Margin Right
|   ├── .m-r-1-px ~ .m-r-1000-px
|   ├── .m-r-n-1-px ~ .m-r-n-1000-px (minus value)
|   ├── .m-r-1 ~ .m-r-100
|   └── .m-r-n-1 ~ .m-r-n-100 (minus value)
├─── Margin Top
|   ├── .m-t-1-px ~ .m-t-1000-px
|   ├── .m-t-n-1-px ~ .m-t-n-1000-px (minus value)
|   ├── .m-t-1 ~ .m-t-100
|   └── .m-t-n-1 ~ .m-t-n-100 (minus value)
├─── Margin Bottom
|   ├── .m-b-1-px ~ .m-b-1000-px
|   ├── .m-b-n-1-px ~ .m-b-n-1000-px (minus value)
|   ├── .m-b-1 ~ .m-b-100
|   └── .m-b-n-1 ~ .m-b-n-100 (minus value)
├─── Padding left
|   ├── .p-l-1-px ~ .p-l-1000-px
|   ├── .p-l-n-1-px ~ .p-l-n-1000-px (minus value)
|   ├── .p-l-1 ~ .p-l-100
|   └── .p-l-n-1 ~ .p-l-n-100 (minus value)
├─── Padding Right
|   ├── .p-r-1-px ~ .p-r-1000-px
|   ├── .p-r-n-1-px ~ .p-r-n-1000-px (minus value)
|   ├── .p-r-1 ~ .p-r-100
|   └── .p-r-n-1 ~ .p-r-n-100 (minus value)
├─── Padding Top
|   ├── .p-t-1-px ~ .p-t-1000-px
|   ├── .p-t-n-1-px ~ .p-t-n-1000-px (minus value)
|   ├── .p-t-1 ~ .p-t-100
|   └── .p-t-n-1 ~ .p-t-n-100 (minus value)
├─── Padding Bottom
|   ├── .p-b-1-px ~ .p-b-1000-px
|   ├── .p-b-n-1-px ~ .p-b-n-1000-px (minus value)
|   ├── .p-b-1 ~ .p-b-100
|   └── .p-b-n-1 ~ .p-b-n-100 (minus value)
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


## Features Lite Edition

> lighter and faster to load but still has all the standard features

Tree view of `configure-lite.css`

```
configure-lite.css
├─── Font
|   ├── .f-break-all
|   ├── .f-uppercase & .f-lowercase
|   ├── .f-left & .f-right
|   ├── .f-center
|   ├── .f-bold & .f-light
|   └── .f-1 ~ .f-100 (%,px)*
├─── Height
|   ├── .h-1-px ~ .h-500-px
|   ├── .h-1 ~ .h-100 (%,vh)*
|   ├── .h-min-1-px ~ .h-min-500-px
|   ├── .h-min-1 ~ .h-min-100 (%,vh)*
|   ├── .h-max-1-px ~ .h-max-500-px
|   └── .h-max-1 ~ .h-max-100 (%,vh)*
├─── Width
|   ├── .w-1-px ~ .w-500-px
|   ├── .w-1 ~ .w-100 (%,vh)*
|   ├── .w-min-1-px ~ .w-min-500-px
|   ├── .w-min-1 ~ .w-min-100 (%,vh)*
|   ├── .w-max-1-px ~ .w-max-500-px
|   └── .w-max-1 ~ .w-max-100 (%,vh)*
├─── Margin left
|   ├── .m-l-1-px ~ .m-l-1000-px
|   ├── .m-l-n-1-px ~ .m-l-n-1000-px (minus value)
|   ├── .m-l-1 ~ .m-l-100
|   └── .m-l-n-1 ~ .m-l-n-100 (minus value)
├─── Margin Right
|   ├── .m-r-1-px ~ .m-r-250-px
|   ├── .m-r-n-1-px ~ .m-r-n-250-px (minus value)
|   ├── .m-r-1 ~ .m-r-100
|   └── .m-r-n-1 ~ .m-r-n-100 (minus value)
├─── Margin Top
|   ├── .m-t-1-px ~ .m-t-250-px
|   ├── .m-t-n-1-px ~ .m-t-n-250-px (minus value)
|   ├── .m-t-1 ~ .m-t-100
|   └── .m-t-n-1 ~ .m-t-n-100 (minus value)
├─── Margin Bottom
|   ├── .m-b-1-px ~ .m-b-250-px
|   ├── .m-b-n-1-px ~ .m-b-n-250-px (minus value)
|   ├── .m-b-1 ~ .m-b-100
|   └── .m-b-n-1 ~ .m-b-n-100 (minus value)
├─── Padding left
|   ├── .p-l-1-px ~ .p-l-250-px
|   ├── .p-l-n-1-px ~ .p-l-n-250-px (minus value)
|   ├── .p-l-1 ~ .p-l-100
|   └── .p-l-n-1 ~ .p-l-n-100 (minus value)
├─── Padding Right
|   ├── .p-r-1-px ~ .p-r-250-px
|   ├── .p-r-n-1-px ~ .p-r-n-250-px (minus value)
|   ├── .p-r-1 ~ .p-r-100
|   └── .p-r-n-1 ~ .p-r-n-100 (minus value)
├─── Padding Top
|   ├── .p-t-1-px ~ .p-t-250-px
|   ├── .p-t-n-1-px ~ .p-t-n-250-px (minus value)
|   ├── .p-t-1 ~ .p-t-100
|   └── .p-t-n-1 ~ .p-t-n-100 (minus value)
├─── Padding Bottom
|   ├── .p-b-1-px ~ .p-b-250-px
|   ├── .p-b-n-1-px ~ .p-b-n-250-px (minus value)
|   ├── .p-b-1 ~ .p-b-100
|   └── .p-b-n-1 ~ .p-b-n-100 (minus value)
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

> **** value available = 1 ~ 5

---

## New Update

> v.1.1.0 

-Color configuration for background and font. 
-configure-lite.css & configure-lite.min.css

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

| <a href="https://github.com/zrafiq111" target="_blank">**Ahmad Zahraturrafiq**</a> |
| :---: |
| [![FVCproductions](https://raw.githubusercontent.com/zrafiq111/User-profile/master/photo.png)]()    |
| <a href="https://github.com/zrafiq111" target="_blank">`github.com/zrafiq111`</a> |

Ahmad Zahraturrafiq<br>
Indonesia

Wa : <a href="https://wa.me/6281312119466?text=Hello%20Zet">+62 81312119466</a><br>
Fb : <a href="https://web.facebook.com/rfq.ns">Ahmad Zet </a>
