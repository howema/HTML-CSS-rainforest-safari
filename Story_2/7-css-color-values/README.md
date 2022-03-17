
# __Rainforest Safari: Chapter 7__

### _"How To Use Color Values with CSS"_

This subdirectory of Philip Zastrow's [How to Style HTML with CSS tutorial series](https://www.digitalocean.com/community/tutorial_series/how-to-style-html-with-css) on DigitalOcean, represents his seventh tutorial installment, ["How To Use Color Values with CSS"](https://www.digitalocean.com/community/tutorials/how-to-use-color-values-with-css)

### _"The 4 Horsemen of..."_

Did I ever think I'd learn how to render colors using numbers? Not really, but I am very much enjoying the ride. Side note, after I've been doing `coding junk` for many hours in a row, my brain turns to mush and I can't use a remote control to select _Fleabag: Season 1, Episode 6_ on a smart tv; a la our beloved _Grandma Howe_. My roommate got a fun chuckle out of that. But hey, I think we'd all make that minor sacrifice for a classic A+ Zastrow tuturial.

In this tutorial, I learned 4 different ways of defining color values with CSS. It's actually quite a relief as this giberish slowly turns to my native language. How strange it is to learn about what you didn't know you didn't know!

Okay, so there's:
1. (100+) keyword color values
2. hexadecimal colors
3. `rgb()` color formation
4. `hsl()` color format


---

##### _Notes of Interest_

<dl>
    <dt>Landmark</dt>
    <dd>area of your design where you draw attention</dd>
    <dt>border-radius</dt>
    <dd>radius of an element's corners</dd>
    <dd>Within this directory, we are using it within the `hr` selector in `styles.css` to round the ends of our line.
    <dd>`<hr />` => horizontal line</dd>
</dl>

Note- `hsl()` offers the benefit of complementary, and more cohesive, color palettes.
* You could, for example, keep two values consistent while only varying the third. 
* This offers a uniformity with a simple soft, gradual transition.

Note- Can achieve a **monochromatic greyscale** by _only_ adjusting the `lightness` value of `hsl()` and not the other two.

##### _In Action_

In our `styles.css`, we created a new combinator to use the `inherit` propery, and called it `footer a`. This was to allow for any `<a>` elements to _inherit_ the values of its parent `<footer>` element. This created the ability for the link within the footer to adhere to the styling of the rest of the footer text, instead of rendering as the default blue for unclicked links.

##### _On Accessibility_

It's important to always use enough color contrast between a `background-color` and the text `color` value.


---

 ## Built With

- HTML
- CSS
- A whole lot of <u>_*Markdown*_</u>.


