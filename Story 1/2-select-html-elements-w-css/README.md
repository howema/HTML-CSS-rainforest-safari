
# __Rainforest Safari: Chapter 2__

### _"How To Select HTML Elements to Style with CSS"_

This subdirectory of Philip Zastrow's [How to Style HTML with CSS tutorial series](https://www.digitalocean.com/community/tutorial_series/how-to-style-html-with-css) on DigitalOcean, represents his second tutorial installment, ["How To Select HTML Elements to Style with CSS"](https://www.digitalocean.com/community/tutorials/how-to-select-html-elements-to-style-with-css)

### _"Talk summary to me"_

In this tutorial, I learned how to efficiently find an html element anywhere on the page, even if it is deeply nested. Once found, we can assign this element specific styles using selectors. You've got your basic type selector, of course, but also the options of both combinator and group selectors. A combinator selector takes advantage of nested html and uses it to form more specific and differing styles even within the same element.

In my `styles.css`, I use a `p strong` combinator selector to tell any text in a strong `element` within a `p` element to render of the color coral. The ancestry reads left to right. Descendents may take after their parents, but with `combinator selectors`, they are not always identical.

In my `styles.css`, I use an `h2, h3, ol strong {}` `group selector` to keep my code DRY and easy to read. I avoid repeating myself when I know that I want all three of those elements to have a `font-weight: normal`.

 ## Built With

- HTML
- CSS
- A whole lot of grit.

