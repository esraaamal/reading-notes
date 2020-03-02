## canvas
looks like the **img** element, with the only clear difference being that it doesn't have the src and alt attributes. Indeed, the **canvas** element has only two attributes, width and height. These are both optional and can also be set using DOM properties. When no width and height attributes are specified, the canvas will initially be 300 pixels wide and 150 pixels high. The element can be sized arbitrarily by CSS, but during rendering the image is scaled to fit its layout size: if the CSS sizing doesn't respect the ratio of the initial canvas, it will appear distorted.


The **canvas** element differs from an **img** tag in that, like for **video**, **audio**, or **picture** elements, it is easy to define some fallback content, to be displayed in older browsers not supporting it, like versions of Internet Explorer earlier than version 9 or textual browsers. You should always provide fallback content to be displayed by those browsers.

#### also canvas not an self closing Element like img..


## Drawing paths

When the current path is empty, such as immediately after calling beginPath(), or on a newly created canvas, the first path construction command is always treated as a moveTo(), regardless of what it actually is. For that reason, you will almost always want to specifically set your starting position after resetting a path.

 ##### When you call fill(), any open shapes are closed automatically, so you don't have to call closePath(). This is not the case when you call stroke().

