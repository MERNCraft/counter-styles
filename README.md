# Counter Styles #

[Demo](https://MERNCraft.github.io/counter-styles)

Demo of how the `@counter-style` at-rule can be used to create custom counters or bullet points for lists.

At the time of writing, the CSS specifications also describe the use of images for counters, but this feature has not been implemented in browsers yet.

The demo also illustrates how the `::marker` pseudo-element can be used to style the tokens used for counting/marking list items. Here the only `color` (sometimes with the `:nth-child()` pseudo-class) has been set, but the [MDN article](https://developer.mozilla.org/en-US/docs/Web/CSS/::marker) describes more properties that can be styled.