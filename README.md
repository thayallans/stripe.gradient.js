# stripe.gradient.js
A clone of the Gradient  on Stripe's landing page (https://stripe.com) but wrapped up into a library for usage.

## Live Demo!
https://thayallan.com/stripe.gradient.js/demo/demo.html

## Installation (CDN)
```
<script src="https://thayallan.com/stripe.gradient.js/src/stripe.gradient.js"></script>
```

## Usage
```javascript
var gradient = new Gradient();
// (id of Canvas, Color #1, Color #2, Color #3, Color #4)
gradient.initGradient("#gradient-canvas", "#ef008f","#6ec3f4", "#7038ff", "#ffba27");
```

## Disclaimer
This is basically just Stripe's gradient code, refactored a bit to make it easy to use as a library.
