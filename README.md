# Little Lemon Homepage: CSS layout and effects demo

This project implements a homepage for the fictional Little Lemon restaurant.  It demonstrates the usage of modern CSS
to layout a page and to provide effects including animation.

This is a pure HTML and CSS page with no JavaScript. To see the page, simply view `index.html` in your browser.

## Layout
The layout uses `display: flex` so that sections resize smoothly when you change the size of your browser window.

Note this page is not optimized for mobile. See https://github.com/rdesantis/react-demo for a truly responsive
mobile-first layout.

## Effects

Some elements, notably the nav bar, use the `:hover` CSS psudo-class to highlight when hovering over them with the mouse.

When you initially load or refresh the page, you will see the text "Try Our New Menu" and a moment later you'll see the text "and Get 20% Off!" fly in from the right of the page to join the original text.  The new text then skews momemtarily to mimic a bounce effect and give emphasis.  These effects are done with a CSS animation.
