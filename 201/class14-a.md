### Transforms&Transitions & Animations
With CSS3 came new ways to position and alter elements. Now general layout techniques can be revisited with alternative ways to size, position, and change elements
### Transform Syntax
The actual syntax for the transform property is quite simple, including the transform property followed by the value. The value specifies the transform type followed by a specific amount inside parentheses
### 2D Transforms 
* 2d Rotate :The transform property accepts a handful of different values. 
* 2D Scale :Using the scale value within the transform property allows you to change the appeared size of an element.
* 2D Translate:The translate value works a bit like that of relative positioning,
* 2D Skew :The last transform value in the group, skew, is used to distort elements on the horizontal axis, vertical axis, or bot
### Transform Origin
As previously mentioned, the default transform origin is the dead center of an element, both 50% horizontally and 50% vertically. To change this default origin position the transform-origin property may be used.
### 3D Transforms  
Working with two-dimensional transforms we are able to alter elements on the horizontal and vertical axes,
* 3D Rotate :Using the rotateX,y,z value
* 3D Scale:By using the scaleZ three-dimensional transform elements may be scaled on the z axis
* 3D Translate:Elements may also be translated on the z axis using the translateZ value
### Backface Visibility
When working with three-dimensional transforms, elements will occasionally be transformed in a way that causes them to face away from the screen
### Transitions & Animations
One evolution with CSS3 was the ability to write behaviors for transitions and animation
### Transition:  an element must have a change in state, and different styles must be identified for each state.
### Transitional Property
property determines exactly what properties will be altered in conjunction with the other transitional properties.
### Transitional Properties
only properties that have an identifiable halfway point. Colors, font sizes
### Transition Duration
he duration in which a transition takes place is set using the transition-duration property. The value of this property can be set using general timing values, including seconds (s) and milliseconds (ms)
### Transition Timing
property is used to set the speed in which a transition will move. 
### Transition Delay
On top of declaring the transition property, duration, and timing function
## Animations
Transitions do a great job of building out visual interactions from one state to another, and are perfect for these kinds of single state changes
* Animations Keyframes:To set multiple points at which an element should undergo a transition
* Animation Name  need to be assigned to an element
* Animation Duration, Timing Function, & Delay
* Animation Iteration
* Animation Direction
* Animation Play State
* Animation Fill Mode

### Shorthand Animations
can be written out in a shorthand format. This is accomplished with one animation property

##  8 SIMPLE CSS3 TRANSITIONS THAT WILL WOW YOUR USERS

1. Fade in :Having things fade in is a fairly common request from clients. It’s a great way to emphasize functionality or draw attention to a call to action.
2. Change color:Animating a change of color used to be unbelievably complex, with all kinds of math involved in calculating separate RGB values and then recombining them
3. Grow & Shrink:To grow an element, you used to have to use its width and height, or its padding.
4. Rotate elements:CSS transforms have a number of different uses, and one of the best is transforming the rotation of an element
5. Square to circle:A really popular effect at the moment is transitioning a square element into a round one, and vice versa.
6. 3D shadow:were frowned upon for a year or so, because they weren’t seen as compatible with flat design, which is of course nonsense, they work fantastically well to give a user feedback on their interactions and work with flat, or fake 3D interfaces.
7. Swing:Not all elements use the transition property. We can also create highly complex animations using @keyframes, animation and animation-iteration.
8. Inset border:One of the hottest button styles right now is the ghost button; a button with no background and a heavy border