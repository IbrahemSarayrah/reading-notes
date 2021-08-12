# Transforms 

* With CSS3 came new ways to position and alter elements, Now general layout techniques can be revisited with 
alternative ways to size, position, and change elements

* All of these new techniques are made possible by the `transform` property and comes in two different settings
> 1. two-dimensional
> 2. three-dimensional

### Transform Syntax

* the transform property is quite simple including the `transform` property followed by the `value`
>
> The `value` specifies the transform type followed by a specific amount inside parentheses

* example

```
div {
  -webkit-transform: scale(1.5);
     -moz-transform: scale(1.5);
       -o-transform: scale(1.5);
          transform: scale(1.5);
}

```
#### 2D Transforms

* 2D Rotate : The rotate value provides the ability to rotate an element from 0 to 360 degrees `transform: rotate(20deg)`

* 2D Scale : Using the scale value within the transform property allows you to change the appeared size of an element `transform: scale(.75)`

* 2D Translate : pushing and pulling an element in different directions without interrupting the normal flow of the document `transform: translateX(-10px)`

* 2D Skew : is used to distort elements on the horizontal axis, vertical axis, or both `transform: skewY(-20deg)`

#### 3D Transforms

* 3D Rotate : we can rotate an element around any axes including rotateX, rotateY, and rotateZ `transform: perspective(200px) rotateZ(45deg)`

* 3D Scale : By using the scaleZ three-dimensional transform elements may be scaled on the z axis `transform: perspective(200px) scaleZ(1.75) rotateX(45deg)`

* 3D Translate : Elements may also be translated on the z axis using the translateZ value `transform: perspective(200px) translateZ(-50px)`

### Transitions

*  for determining styles for different states is by using the `:hover`, `:focus`, `:active`, and `:target` **pseudo-classes.**

* example

```

.box {
  background: #2db34a;
  transition-property: background;
  transition-duration: 1s;
  transition-timing-function: linear;
}
.box:hover {
  background: #ff7b29;
}

```

####Transitional Property 

* The `transition-property` property determines exactly what properties will be altered in conjunction with the other transitional properties
only the properties identified within the `transition-property` value will be affected by any transitions.

### Animations

* Animation is a CSS property that allows for animation of most HTML elements (such as div, h1 and span) without JavaScript or Flash.

* The `@keyframe`s rule includes the animation name, any animation breakpoints, and the properties intended to be animated.

* example 

```
@keyframes slide {
  0% {
    left: 0;
    top: 0;
  }
  50% {
    left: 244px;
    top: 100px;
  }
  100% {
    left: 488px;
    top: 0;
  }
}
```