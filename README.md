# Admin Dashboard

[Live link](https://lbackman.github.io/admin-dashboard/)

This final project in Intermediate HTML and CSS fittingly combined elements from the entire course.

I got ample use out of Emmet shortcuts when building the HTML structure, and to a lesser degree when writing CSS.

I used custom properties for reusing certain values in CSS.

I used pseudo-classes and psuedo-elements to make a responsive design.
For instance: To make the project card shadow grow at the same rate as the translation in the y-axis,
I used an ::after pseudo-element with the same shape as the card, but a larger shadow. The opacity of the pseudo-
element is 0 by default but increseases to 1 as the cursor hovers over the card.

I made use of SVGs; both inline and linked. The inline SVGs are easier to style directly, e.g. fill color, but the
HTML can become clunky. Linked SVGs are handier when resued many times, like in the project cards.

I positioned ::after pseudo-elements absolutely in relation to their relatively positioned "parent" elements.

Throughout the project, I used CSS function such as clamp(), translateY(), minmax() and repeat().

I made sure that the page should behave and look similarly in a range of different web browsers, like Chrome, Fire-
fox and Safari. I used -webkit-transform, and so on to make the transitions as smooth in Safari as in Chrome.

I even used a form element in the header, albeit only with one input element.

And of course, the main goal of the project, CSS Grid, is heavily featured throughout the project.

The entire page consists of grid containers within grid containers.
In the body I used grid-template and used strings and grid-area in the header, sidebar and main to define the layout.
In most smaller grids I used only grid-template-columns and let the rows be defined inplicitly.
When making the grid in the "projects" part though I defined the first row to be the height of the heading (Your
Projects), and then defined grid-auto-rows to be the height of the individual cards.
Except for implementing grid-area in the main grid I mostly used column numbers when defining layout.
