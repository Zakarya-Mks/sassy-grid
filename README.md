# sassy-grid (a basic 12 column grid responsive framework)

## features

```bash
a basic **12 column grid** framework based on flex box.
its fully responsive and easy to implement,
**inspired by bootstrap 4 class names**, all you have to do is use the class name you need.

how to use:

** display **
```

-.d-[none | block | inline | inline-block | flex | grid | table] : to specify the display property.
-.d-[sm | md | lg | xl]-[none | block | inline | inline-block | flex | grid | table] : responsively change the display property based on the device width.

```

** the grid **
```

\*grid-row
-.row : the grid columns main container it span 12 columns and occupy up to 1140px in width.

- grid columns
  -.col-1 to .col-12 : to specify your column width. (how many column to span).
  -.col-[sm | md | lg | xl]-_: responsively specify the column width. based on the devise width _(from 1 to 12).
  _column-order
  -.order-0 | .order-1 to .order-12: will reorder your column based on the chosen index.
  -.order-[sm | md | lg | xl]-_: responsively specify the order based on the device width *(from 1 to 12).
  *offset-columns
  -.offset-0 | .offset-1 to .offset-12 : offset a column by (the index) number of column.
  -.offset-[sm | md | lg | xl]-_ : responsively offset the column based on the device width _(from 1 to 12).

```
** flex box **
```

- flex-direction
  -.flex-[row | row-reverse | column | column-reverse] : change the flex-box flex-direction property.
  -.flex-[sm | md | lg | xl]-[row | row-reverse | column | column-reverse] : responsively change the flex-box flex-direction property based on the device width..
- flex-wrap
  -.flex-[nowrap | wrap | wrap-reverse] : change the flex-box flex-wrap property.
  -.flex-[sm | md | lg | xl]-[nowrap | wrap | wrap-reverse] : responsively change the flex-box flex-wrap property based on the device width..
- justify-content
  -.justify-content-[start | end | center | between | around | evenly] : change the flex-box justify-content property.
  -.justify-content-[sm | md | lg | xl]-[start | end | center | between | around | evenly] : responsively change the flex-box justify-content property based on the device width.
- align-[items | self]
  -.align-[items | self]-[start | end | center | stretch | baseline] : change the flex box align-items | align-self property.
  -.align-[items | self]-[sm | md | lg | xl]-[start | end | center | stretch | baseline] : responsively change the flex box align-items | align-self property based on the device width.
- align-content
  -.align-content-[start | end | center | stretch | between | around]: change the flex box align-content property.
  -.align-content-[sm | md | lg | xl]-[start | end | center | stretch | between | around]: responsively change the flex box align-content property based on the device width.

```

** padding and margin utilities **
```

- padding
  -.p-1 to .p-5: change the padding property on all sides.
  -.p-[sm | md | lg | xl]-_: responsively change the padding property on all sides based on the device width.
  -.p[x | y]-_: change the padding property on the desired axis.
  -.p[x | y]-[sm | md | lg | xl]-_: responsively change the padding property on the desired axis based on the device width.
  -.p[t | r | b | l]-_: change the padding property on the desired side.
  -.p[t | r | b | l]-[sm | md | lg | xl]-\*: responsively change the padding property on the desired side based on the device width.
- margin
  -.m-1 to .m-5: change the margin property on all sides.
  -.m-[sm | md | lg | xl]-_: responsively change the margin property on all sides based on the device width.
  -.m[x | y]-_: change the margin property on the desired axis.
  -.m[x | y]-[sm | md | lg | xl]-_: responsively change the margin property on the desired axis based on the device width.
  -.m[t | r | b | l]-_: change the margin property on the desired side.
  -.m[t | r | b | l]-[sm | md | lg | xl]-\*: responsively change the margin property on the desired side based on the device width.

\*size
-1: .5rem.
-2: .75rem.
-3: 1rem.
-4: 1.5rem.
-5: 2rem.

```

** text utilities **
```

- text colors
  -.text-[primary | secondary | success | warning | info | danger | light | dark | black | gold]: change the color property based on a predefined colors theme.
  \*text position
  -.text-[center | left | right | justify]: change the text-align property.
  -.text-[sm | md | lg | xl]-[center | left | right | justify]: responsively change the text-align property based on the device width.

```
** background colors **

```

    -.bg-[primary | secondary | success | warning | info | danger | light | dark | black | gold]: change the background-color property based on a predefined colors theme.

```

** borders **
```

    -.border-0: set the border property to none.
    -.border-[sm | md | lg | xl]-0: responsively set the border property to none based on the device width.
    -.border: set the border property to solid 1px #dee2e6
    -.border-[top | right | bottom | left]: set the border on a single side.
    -.border-[primary | secondary | success | warning | info | danger | light | dark | black | gold] : change the color of the borders based on a predefined colors theme.
    -.rounded: set the border-radius property to 0.25rem (slightly rounded border)
    -.rounder-0: set the border-radius property to 0 (right angles).
    -.rounded-circle: set the borders to a rounded shape.
    -.rounded-pill: set the border to a pill shape.
    -.rounded-[sm | lg]: increase or decrees the border roundness.

```

```

## Built With

- [Sass](https://sass-lang.com/)

## Demos

> - [Cloning The Odin Project](https://zakarya-mks.github.io/sassy-grid/) :shipit:
