Flexit
======

Flexit is a small set of CSS classes for rapidly creating fixed height application layouts using CSS Flexbox.

If you want to use Flexit in production you need to consider browser support. CSS Flexbox is currently supported by the latest
releases of all major browsers.
For support in older browser releases see: http://caniuse.com/#search=flexbox

##Usage
Flexit is intended for fixed height application layouts but can also be inside a single div. If you are using it for a
full screen application you need to set the height of the html and body tag to 100% by adding the class .hf to both. If you are using it
inside a single div that div needs a fixed height.

Flexit has 2 container classes, .hbox will stack its children horizontally and .vbox vertically. Additional classes will add gap between the
children, padding, scrolling and center them horizontally or vertically (omg!). You can add a .flex class to containers that you want to
grow to fill available space in the parent container.

## Example
The example below (example.html) is created with Flexit. The body element has a .debug class. This adds background color and border to
all children to make it easier to debug your layout.

##Inspiration
Flexit is inspired the HBox and VBox containers in Adobe Flex (AS3) and Stubbornellas ideas around object oriented CSS.
https://github.com/stubbornella/oocss/wiki.

## License
