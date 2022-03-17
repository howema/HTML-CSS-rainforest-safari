
# __Rainforest Safari: Chapter 6__

### _"How To Lay Out Text with CSS"_

This subdirectory of Philip Zastrow's [How to Style HTML with CSS tutorial series](https://www.digitalocean.com/community/tutorial_series/how-to-style-html-with-css) on DigitalOcean, represents his sixth tutorial installment, ["How To Lay Out Text with CSS"](https://www.digitalocean.com/community/tutorials/how-to-lay-out-text-with-css)

### _"The Sum of All Things"_

In Chapter 6 of our design adventure, we learn the crucial art of _**text layout**_ which defines the balance between the _**spacing**_, between words, lines, and blocks of content. We aim for spacings- neither too big or too small- that accentuate both accessibility and design. Along with ideal height and space between words, we also aim for the ideal _**width**_ of a line of text, using `ch`, or characters, as our unit.

Clarissa Peterson's _ideal line length_ principle of using only 45-75 characters, was pretty surprising for me. It's not something you normally consciously think about, and yet it's always there. Well, it better be. I now know that it offers balance between 1. preventing eye fatigue (from constantly moving between short lines), and 2. prevents the user from losing track of their current (too long) of a line.


_**Notes of Interest**_

Note- Format capitalization with `text-transform` (3 options).

Note- Place font properties on the same line with `font` shorthand (many options).

--------------------

Note- `margin`, when used within a text focused type selector (like `<h1>`), can be used to center/move the content around the page. (Plays with the amount of space between each the content and the edge of your browser).

Note- when `margin`properties of 2 elements overlap, the greater value overrides the lesser.

Define- `margin` = control of space between (**outside**) the elements themselves / differing blocks of content

Define- a _baseline_ is 'the line on which the bottom of text rests.'
(Often used with `line-height`)

Define- `line-height`: the space between lines **within** an element.

Summary--So when you add `letter-spacing` to `margin` and `line-height`, you recieve the ability to manipulate between letters, lines, and elements; respectively.

--------------------

Define- an _adjacent sibling combinator_ is the `+` sign that combines two selectors. 
A new type selector is created between these two which: 1. features the element represented in the first selector, 2. a plus sign, and 3. then the element in the second selector. 

_**The Proof is in the Pudding**_
The `styles` file in this directory features this tool by placing  `h3 + p` selector between the `h3` and `p` selectors in order to only apply very specific styling to the `p` element only when immediately preceded by the `h3` element. 
In this case specifically, there will be more space between `h3` elements and `p` elements than normal. The other `p` elements are unaffected.

--------------------


_**Remember**_
<<<<<<< HEAD
<<<<<<< HEAD
`em` => _proportional_ to `font-size` ==> (here we see it used within `styles.css` for `line-spacing`)
`em` => _relative_ to `font-size` of its element / parent
* example: if the **parent `font-size` is 18px, 1em = 18px**
=======
`em` => _proportional_ to `font-size` ==> (here we see it used within `styles.css` for `line-spacing`) 
>>>>>>> 963e52b (🎨 feat: add tutorials 6 + 7)
=======
`em` => _proportional_ to `font-size` ==> (here we see it used within `styles.css` for `line-spacing`)
`em` => _relative_ to `font-size` of its element / parent
* example: if the **parent `font-size` is 18px, 1em = 18px**
>>>>>>> 5a28d87 (📝 docs: clarify em relational nature)
`em` => 1em = default `font-size` of document (usually 16px)

 ## Built With

- HTML
- CSS
- A whole lot of relativity.


