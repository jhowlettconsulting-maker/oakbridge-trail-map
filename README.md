# Oakbridge Trail Map

[Open the public map](https://jhowlettconsulting-maker.github.io/oakbridge-trail-map/)

The v7 course descriptions are included. The map responds to the actual embed container width, including live container resizing. Wide containers show the full map; containers below 960 px use the vertical trail. Below 600 px, controls and course details adapt for mobile.

## Wix embed

Paste this into a Wix Embed HTML element. It fills the element width and height. Set the element size in Wix at each breakpoint (for example, 900 px high on desktop and tablet, 800 px high on mobile). The map scrolls inside the element when its content is taller; Wix controls the outer element height.

```html
<iframe
  src="https://jhowlettconsulting-maker.github.io/oakbridge-trail-map/"
  title="The Oakbridge Path — Course Trail Map"
  width="100%"
  height="100%"
  style="display:block;width:100%;height:100%;border:0;"
  loading="lazy">
</iframe>
```
