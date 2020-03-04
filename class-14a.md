# new techniques are made possible by the transform property

-webkit-transform: scale(1.5);
-moz-transform: scale(1.5);
-o-transform: scale(1.5);
 transform: scale(1.5);

### 2D Transforms two-dimensional-transforms
Elements may be distorted, or transformed, on both a two-dimensional 
plane or a three-dimensional plane. 

 ### The transition-property property determines exactly what properties will be altered in conjunction with the other transitional properties.

 It is important to note, ***not all properties may be transitioned**, only properties that have an identifiable halfway point. Colors, font sizes, 

## Transition Duration 
in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms).

### Transition Timing:
The transition-timing-function property is used to set the speed
this property include linear, ease-in, ease-out, and ease-in-out.

***The linear keyword value identifies a transition moving in a constant speed from one state to another. The ease-in value identifies a transition that starts slowly and speeds up throughout the transition, while the ease-out value identifies a transition that starts quickly and slows down throughout the transition. The ease-in-out value identifies a transition that starts slowly, speeds up in the middle, then slows down again before ending.***

When transitioning multiple properties, you can identify multiple timing functions. These timing function values, as with other transition property values, may be declared as comma separated values.

  - transition-property: background, border-radius;
  - transition-duration: .2s, 1s;
  - transition-timing-function: linear, ease-in;

