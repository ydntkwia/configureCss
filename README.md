# ConfigureCSS

No more editing css for a long time. <br>
This is very suitable for use as a complement to the CSS framework that you are using.

> ConfigureCSS is not a responsive framework css like `bootstrap` and etc. This is only complement css

---

## Table of Contens

- [Installation](#Installation)
- [Example](#Example)
- [Features](#Features)
- [New Update](#New-Update)
- [Next Update](#Next-Update)
- [Creator](#Creator)

---

## Installation

Import `configure.css` into your project.<br>
```html
<link rel="stylesheet" type="text/css" href="Path/to/configure.css">
```
or inside your css file
```css
@import url(Path/to/configure.css);
```
And if you don't want to download it, you can use this link.
```html
<link rel="stylesheet" type="text/css" href="https://zrafiq111.netlify.com/configure.css">
```

---

## Example

> You can add the class and add it inside the tag html you want to edit. <br>

<img src="https://raw.githubusercontent.com/zrafiq111/User-profile/master/before.png" width="75%">

```html
<h2 class=" fw-8 grey-8-font" data-animate="ts-fadeInUp">APA KATA MEREKA?</h2>
<blockquote class="blockquote mt-150px">
  <figure>
    <aside>
      <i class="fa fa-quote-right"></i>
    </aside>
   <div class="ts-circle__lg"></div>
  </figure>
  <p class=" f-center grey-5-font ">
  Morbi et nisl a sapien malesuada scelerisque. Suspendisse tempor turpis mattis nibh posuere. Aenean sagittis nisl.
  uthicula sagitti
  </p>
  <footer class="blockquote-footer">
  <h4 class=" red-7-font f-up fw-6 ">Ahmad Zahraturrafiq</h4>
  <h6 class=" red-6-font fw-5 ">SMKN 1 CIREBON</h6>
  </footer>
</blockquote>
```

<img src="https://raw.githubusercontent.com/zrafiq111/User-profile/master/AFTER.png" width="75%">

The structure:

- `fw`,`f`,`red`,`grey`  = for the category of class
- `8`,`150px`,`center`,`7`,`6`,`5` = size or sub-category of class
- `font` = sub-category-2 class

---

## Features

Tree view of `configure.css`

```
configure.css
├─── Font
|   ├── .f-break
|   ├── .f-up & .f-low
|   ├── .f-left & .f-right
|   ├── .f-center
|   ├── .f-bold & .f-light
|   └── .f-1 ~ .f-100 (%,px)*
├─── Height
|   ├── .h-1px ~ .h-750px
|   ├── .h-1 ~ .h-100 (%,vh)*
|   ├── .hmin-1px ~ .hmin-750px
|   ├── .hmin-1 ~ .hmin-100 (%,vh)*
|   ├── .hmax-1px ~ .hmax-750px
|   └── .hmax-1 ~ .hmax-100 (%,vh)*
├─── Width
|   ├── .w-1px ~ .w-750px
|   ├── .w-1 ~ .w-100 (%,vh)*
|   ├── .wmin-1px ~ .wmin-750px
|   ├── .wmin-1 ~ .wmin-100 (%,vh)*
|   ├── .wmax-1px ~ .wmax-750px
|   └── .wmax-1 ~ .wmax-100 (%,vh)*
├─── Margin left
|   ├── .ml-1px ~ .ml-250px
|   └── .mln-1px ~ .mln-250px (minus value)
├─── Margin right
|   ├── .mr-1px ~ .mr-250px
|   └── .mrn-1px ~ .mrn-250px (minus value)
├─── Margin top
|   ├── .mt-1px ~ .mt-250px
|   └── .mtn-1px ~ .mtn-250px (minus value)
├─── Margin bottom
|   ├── .mb-1px ~ .mb-250px
|   └── .mbn-1px ~ .mbn-250px (minus value)
├─── Padding left
|   ├── .pl-1px ~ .pl-250px
|   └── .pln-1px ~ .pln-250px (minus value)
├─── Padding right
|   ├── .pr-1px ~ .pr-250px
|   └── .prn-1px ~ .prn-250px (minus value)
├─── Padding top
|   ├── .pt-1px ~ .pt-250px
|   └── .ptn-1px ~ .ptn-250px (minus value)
├─── Padding bottom
|   ├── .pb-1px ~ .pb-250px
|   └── .pbn-1px ~ .pbn-250px (minus value)
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
    ├── .fw-1 ~ .fw-10 (font-weight)
    ├── .border-round
    └── .border-0

```

` * `units available 

` **`if the unit class name is empty the unit will automatically go to percent 
 
` ***` color available = `grey` , `red` , `green` , `blue`, `yellow` 

` ****` available values = 1 ~ 10 

---


## New Update

> v.1.1.5 

- +Colour configuration for background and font. 

---

## Next Update

> All updates will be there every once a week <br>

Next update:

- Line height
- Color custom
- Customizable `configure.css`

For request update just email me : <a href="mailto:achmad.zahra62@gmail.com">achmad.zahra62@gmail.com</a>

---

## Creator

| <a href="http://zet.rf.gd/" target="_blank">**Ahmad Zahraturrafiq**</a> |
| :---: |
| [![zrafiq111](https://raw.githubusercontent.com/zrafiq111/User-profile/master/photo.png)]()    |
| `Indonesia` |


Wa : <a href="https://wa.me/6281312119466?text=Hello%20Zet">+62 81312119466</a><br>
Fb : <a href="https://web.facebook.com/rfq.ns">Ahmad Zet </a>
