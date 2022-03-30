
# __Rainforest Safari: Chapter 11 __

### _"How To Use Float and Columns to Lay Out Content with CSS"_

This subdirectory of Philip Zastrow's [How to Style HTML with CSS tutorial series](https://www.digitalocean.com/community/tutorial_series/how-to-style-html-with-css) on DigitalOcean, represents his eleventh tutorial installment, ["How To Use Float and Columns to Lay Out Content with CSS"](https://www.digitalocean.com/community/tutorials/how-to-use-float-and-columns-to-lay-out-content-with-css)

### _"Description"_

This repo goes into depth about the `float` property, which creates elements able to be wrapped in content,
as well as the `columns` property- to break content up evenly and flow between columns.

These bring their own unique strengths which are nnot always possible with the `Grid` and `Flexbox` properties alone.


`column` property
* _Sets params for applying columns to text_
* `column-gap`
* `column-rule` - vertical line between columns (styled like a border)
* On mobile, we'd generally use 1 `column`
- On a wide enough screen, we could use 3.
* `break-inside`, `break-after`, `break-before` to control column flow
* Is a shorthand itself
* Consider styling your margins, margin-bottoms/etc
* Account for messy default stylings
* Great for lists


`float` property
* _"Allows inline elements to wrap around a floating element"_
* 3 Options - `left`, `right`, `none`
* Use `clear` (`left`, `right`, or `both`) property to counteract `float`
* Great for use with `blockquote`
* Use negative `margin` values to pull outside the layout

Media Queries
* Prioritize use of `max-width: 100%` over `width: 100%` to avoid distorting, or pixelizing, the image


---

##### _In Action_

We added a responsive breakpoint with `@media (min-width: 80rem) {}` and added `columns: 3` since a wide screen would welcome 3 columns. In the same query, we added a negative margin value to the floating image element - visually optimizing just what a `float` can really do. The right `margin` was set to `-40%`, pulling the image outside & to the right of the content by 40% of the **parent element's width** (not the image width.)


##### _Of Note_

* 1 `ch` = 1 zero character of the set `font-size` value
* _Review combinator vs sister(?) selector_
* The pseudoclass `:first-child` is used to scope styles (which child of the parent will be affected by styling).

 _"Three requirements for effective responsive web design:"_
 1. flexible width
 2. resizable images
 3. media queries

##### _On Accessibility_

* Always be sure to add that alt text on images for users of screen readers.

---

 ## Built With

- HTML
- CSS

