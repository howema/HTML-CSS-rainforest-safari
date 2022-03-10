
# __Rainforest Safari: Chapter 1__

### _"How To Apply CSS Styles to HTML with Cascade and Specificity"_

This subdirectory of Philip Zastrow's [How to Style HTML with CSS tutorial series](https://www.digitalocean.com/community/tutorial_series/how-to-style-html-with-css) on DigitalOcean, represents his first tutorial installment, ["How To Apply CSS Styles to HTML with Cascade and Specificity"](https://www.digitalocean.com/community/tutorials/how-to-apply-css-styles-to-html-with-cascade-and-specificity)

### _"Please describe this tutorial to me using strange analogies"_

 Through this tutorial, I learned the real definition of Cascading Style Sheets. It's a waterfall that we won't fight to go upstream, and a hierarchy of kings to be always honored. The social order is that some selectors are just more important than others, like how in my example, the class selector is more important, and will usually override the element selector. In my styles.css, I tried swapping `strong` and `.highlight` and it did not make a difference. There are rules that must be observed!! A princess always comes before a commoner. 
 
 BUT there are exceptions to every rule. With the implementation a trick or two, a mere peasant could swap places with a prince and finally rule them all. In my example, a style attribute was placed on the `strong` selector directly in-line in index.js, attempting to make red the ruling class. Yay to the people! Long live the power of in-line styles. 
 
 But oh no no no. Not so fast. It's blue with the final say here, due to the retaliation of the `!important` rule that has been added to the `strong` attribute in styles.css. Here we can see the rich get richer, and how nothing really changes.

 ## Built With

- HTML
- CSS
- A whole lot of love.

