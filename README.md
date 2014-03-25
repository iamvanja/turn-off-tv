# Old TV turn off animation

This simple jQuery plugin creates a turn off animation of an old TV in the current browser viewport. Its use is meant for situations when the user is logging out or is deleting the content currently on the screen etc.
It will create the animation and load the url provided in the href attribute of the targeted element.

Feedback, bugs, questions? [E-mail](mailto:vanja@gavric.org) me, I'll respond quickly!

## Demo
- Demo can be found on [link](http://vanja.gavric.org/playground/turn-off-tv/).

## Getting started
#### 1. Load jQuery and `jquery.turn-off-tv.js` right before your closing `</body>` tag
```html
<script src="jquery-1.10.2.min.js"></script>
<script src="jquery.turn-off-tv.min.js"></script>
```

#### 2. Include the css file inside `<head>`
```html
<link rel="stylesheet" href="turn-off-tv.css">
```

#### 3. Call old-tv on an tag that links to a page (has a href attribute)
```html
<script>
  $('#element').turnOffTV();
</script>
```

## Options
#### bodyWrapId 
  Change id of the body wrapper (make sure to change the CSS as well)    
  default = body-wrap

#### tvBoxId
  Change id of the old tv element (make sure to change the CSS as well)  
  default = tv-box

#### tvColor
  Change color of the tv, css value in rgb or hex  
  default = #000
