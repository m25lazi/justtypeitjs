# justtypeitjs
Simple javascript library for adding typewriting effect to the web pages

# Usage
Provides easiest way to add typewriting effect

Create array of elements that have to be written using : 
```
function typingElement(id, speed, delay)
```

Call *justTypeIt* API wherever you want to start typing, whether its when a page is loaded or when an event is fired.
```
function justTypeIt(elementsArray)
```

# Example
```
$(document).ready(function(){
    justTypeIt([typingElement('#firstElement', 300, 500), 
                typingElement('#nextElement', 100, 0)]);
});
```

# Thanks To
Base code is from http://codepen.io/voronianski/pen/aicwk
http://pixelhunter.me/

Change from the base code is that this library takes an array of elements with typing speed, post write delay for each element and renders page by itself.
