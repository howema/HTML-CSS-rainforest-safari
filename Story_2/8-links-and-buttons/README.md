
# __Rainforest Safari: Chapter 8__

### _"How To Use Links and Buttons with State Pseudo-Classes in CSS"_

This subdirectory of Philip Zastrow's [How to Style HTML with CSS tutorial series](https://www.digitalocean.com/community/tutorial_series/how-to-style-html-with-css) on DigitalOcean, represents his eighth tutorial installment, ["How To Use Links and Buttons with State Pseudo-Classes in CSS"](https://www.digitalocean.com/community/tutorials/how-to-use-links-and-buttons-with-state-pseudo-classes-in-css)

### _"Summary"_

This tutorial was about providing different styling to various **interactive element states**. This means that the state of an element changes, especially when triggered by the user. And different states require different (and deliberate/distinct) styling.

### _"Summary Breakdown"_

The `<button>` and `<a>` elements are used for different purposes, but on the UX side, we generally treat them the same.

Primary state pseudo-classes:
* :hover
* :active
* :focus
* :visited

transition
* property that creates/customizes animation between states
* is shorthand for collection of transition-specs
* makes interactive elements more engaging

---

### _"Thinking Out Loud"_

Ok, now I get it. In `styles.css` in this directory, `.button` is used to emulate `<button>` so that it is more customizable and can apply to _both_ `<button>` and `<a>`. We want to do this for the user experience aspect, so that the stylings match up easily. When styled, a user won't know that the "button" they chose to go to a new page is actually a link (and not an actual "button," which is only used for state changes and actions--_not_ redirection). 

Pseudo-classes (PS) are placed right beneath their original/corresponding _regular_ type selector, as their _own_, _new_ type selector. They are just that original element appended with a colon and the name of the condition. 

In `styles.css` in this directory, there's an `a` selector, but also an `a:hover` selector right below it, which contains the new instructions/stylings to be used when we _hover_ over _a_.

---

##### _Notes/Trickier Definitions_

<dl>
    <dt>pseudo-class</dt>
    <dd>special group of CSS conditions that allow state changes to initiate style changes</dd>
    <dt>:focus</dt>
    <dd>change styles when navigating page with keyboard</dd>
    <dt>transition</dt>
    <dd>property that creates/customizes animation between states</dd>
</dl>

* It seems that there are _both_ a small handful of pre-defined pseudo-classes in CSS (i.e. :hover) and also the ability to create your own pseudo-class, like we did by creating `.button`.

* `:visited` ==> inactive/requires action from user in the past (unlike the other 3, which require live action from the user) 
- This PS will also often require appending some of the other PS conditions like `:hover`, `:active`, etc.
+ Watch out for this... it's a whole thing.
+ Example ==> you'd stick `a:visited:hover` within the same type selector of `a:hover`, but right below it
+ Cont. ==> the type selector is now transformed into `a:hover, a:visited:hover`

---

 ## Built With

- HTML
- CSS
- A whole lot of interest.