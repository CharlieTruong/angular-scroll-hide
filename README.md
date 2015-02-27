#Angular Scroll Hide
Angular directive to scroll up position fixed elements while an associated element scrolls down and re-displays on scroll up.

#Installation
```
bower install angular-scroll-hide --save
```

#Usage
Add the module `scrollHide` to your angular project.  Add this directive to your element.

Pass the pixel limit to scroll the element to the directive.  This is typically the 
element height.

Pass the css selector to the associated scrolling element to which the hiding element should bind.

To hide this element behind another one on scrolling, you will need to handle that in your own template and manage the stacking contexts as needed in your stylesheets.

```
<div scroll-hide="25" scrolling-element="#scrolling">Hello World</div>
```
