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

<img src="https://raw.githubusercontent.com/zrafiq111/User-profile/master/before.png" width="60%">

```html
<h2 class=" `fw-8` `grey-8-font` " data-animate="ts-fadeInUp">APA KATA MEREKA?</h2>
<blockquote class="blockquote mt-150px">
  <figure>
    <aside>
      <i class="fa fa-quote-right"></i>
    </aside>
   <div class="ts-circle__lg"></div>
  </figure>
  <p class=" `f-center` `grey-5-font` ">
  Morbi et nisl a sapien malesuada scelerisque. Suspendisse tempor turpis mattis nibh posuere. Aenean sagittis nisl.
  uthicula sagitti
  </p>
  <footer class="blockquote-footer">
  <h4 class=" `red-7-font` `f-up` `fw-6` ">Ahmad Zahraturrafiq</h4>
  <h6 class=" `red-7-font` `fw-5` ">SMKN 1 CIREBON</h6>
  </footer>
</blockquote>
```

<img src="https://raw.githubusercontent.com/zrafiq111/User-profile/master/AFTER.png" width="60%">

The structure:

- `h`  = for the type of class
- `250` = size of class
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
|   ├── .h-1 ~ .h-100 (px,pt,em)*
|   ├── .h-1 ~ .h-100 (%,vh)*
|   ├── .h-min-1 ~ .h-min-750 (px,pt,em)*
|   ├── .h-min-1 ~ .h-min-100 (%,vh)*
|   ├── .h-max-1 ~ .h-max-750 (px,pt,em)*
|   └── .h-max-1 ~ .h-max-100 (%,vh)*
├─── Width
|   ├── .w-1 ~ .w-100 (px,pt,em)*
|   ├── .w-1 ~ .w-100 (%,vh)*
|   ├── .w-min-1 ~ .w-min-750 (px,pt,em)*
|   ├── .w-min-1 ~ .w-min-100 (%,vh)*
|   ├── .w-max-1 ~ .w-max-750 (px,pt,em)*
|   └── .w-max-1 ~ .w-max-100 (%,vh)*
├─── Margin left
|   ├── .m-l-1-px ~ .m-l-500-px
|   ├── .m-l-n-1-px ~ .m-l-n-500-px (minus value)
|   ├── .m-l-1 ~ .m-l-100
|   └── .m-l-n-1 ~ .m-l-n-100 (minus value)
├─── Margin Right
|   ├── .m-r-1-px ~ .m-r-500-px
|   ├── .m-r-n-1-px ~ .m-r-n-500-px (minus value)
|   ├── .m-r-1 ~ .m-r-100
|   └── .m-r-n-1 ~ .m-r-n-100 (minus value)
├─── Margin Top
|   ├── .m-t-1-px ~ .m-t-500-px
|   ├── .m-t-n-1-px ~ .m-t-n-500-px (minus value)
|   ├── .m-t-1 ~ .m-t-100
|   └── .m-t-n-1 ~ .m-t-n-100 (minus value)
├─── Margin Bottom
|   ├── .m-b-1-px ~ .m-b-500-px
|   ├── .m-b-n-1-px ~ .m-b-n-500-px (minus value)
|   ├── .m-b-1 ~ .m-b-100
|   └── .m-b-n-1 ~ .m-b-n-100 (minus value)
├─── Padding left
|   ├── .p-l-1-px ~ .p-l-500-px
|   ├── .p-l-n-1-px ~ .p-l-n-500-px (minus value)
|   ├── .p-l-1 ~ .p-l-100
|   └── .p-l-n-1 ~ .p-l-n-100 (minus value)
├─── Padding Right
|   ├── .p-r-1-px ~ .p-r-500-px
|   ├── .p-r-n-1-px ~ .p-r-n-500-px (minus value)
|   ├── .p-r-1 ~ .p-r-100
|   └── .p-r-n-1 ~ .p-r-n-100 (minus value)
├─── Padding Top
|   ├── .p-t-1-px ~ .p-t-500-px
|   ├── .p-t-n-1-px ~ .p-t-n-500-px (minus value)
|   ├── .p-t-1 ~ .p-t-100
|   └── .p-t-n-1 ~ .p-t-n-100 (minus value)
├─── Padding Bottom
|   ├── .p-b-1-px ~ .p-b-500-px
|   ├── .p-b-n-1-px ~ .p-b-n-500-px (minus value)
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

` * `units available 

` **`if the unit class name is empty the unit will automatically go to percent 
 
` ***` color available = `grey` , `red` , `green` , `blue`, `yellow` 

` ****` available values = 1 ~ 10 

---


> Lite Version

More faster and more light to load.

- values height and width are limited to 500px
- values margin and padding are limited to 250px
- units available only `%`, `px`, `vw` and `vh`
- Available values for color = 1 ~ 5

---

> All Version

More available values.

- values height, width, margin, and padding are limited to 1000(px,pt,em) 

---


## New Update

> v.1.1.0 

- +Colour configuration for background and font. 
- +configure-lite.css & configure-lite.min.css

---

## Next Update

> All updates will be there every once a week <br>

Next update:

- Line height
- Color custom
- All font Weight
- All padding and margin configuration

For request update just email me : <a href="mailto:achmad.zahra62@gmail.com">achmad.zahra62@gmail.com</a>

---

## Creator

| <a href="http://zet.rf.gd/" target="_blank">**Ahmad Zahraturrafiq**</a> |
| :---: |
| [![zrafiq111](https://raw.githubusercontent.com/zrafiq111/User-profile/master/photo.png)]()    |
| `Indonesia` |


Wa : <a href="https://wa.me/6281312119466?text=Hello%20Zet">+62 81312119466</a><br>
Fb : <a href="https://web.facebook.com/rfq.ns">Ahmad Zet </a>
