
# __Rainforest Safari: Chapter 5__

### _"How To Use Common Units in CSS"_

This subdirectory of Philip Zastrow's [How to Style HTML with CSS tutorial series](https://www.digitalocean.com/community/tutorial_series/how-to-style-html-with-css) on DigitalOcean, represents his fifth tutorial installment, ["How To Use Common Units in CSS"](https://www.digitalocean.com/community/tutorials/how-to-use-common-units-in-css)

### _"TIL"_

This was a pretty cool tutorial. I learned a ton but the first thing that comes to mind is the fact that `px` is a physical unit, representing the attributes of a screen.

Another interesting tidbit is how we should aim to frame our thinking for `font-size` as a sort of context-within-context. The value of the `em` unit is based on the relative font-size of it's parent. Of course, this is calculated with our beloved `target / context` formula. The only different here is the context is more local than usual, simply being the parent and not the default within the doc.

The `rem` unit is short for "root element" (root = **the topmost element of the webpage**, i.e. `<html>`, `<body>`) and is _also_ a <u>relative</u> unit like its friend `em`. It's parent/context, however, is always based upon the `font-size` value of the `root` element. 

This means that when the default `font-size` of `16px` is used, `em` and `rem` are interchangable, as demonstrated in the `.excerpt` type selector in my `styles` page, found in this directory. 

If you look further down the page, we have a different story. The `.citation` selector was originally calculated with the context of use of a `14px` size font. So to convert these values from `em` to `rem`, they need to be recalculated with the root element default of `16px` in mind.

 ## Built With

- HTML
- CSS
- A whole lot of math.


