# iOS PointerEvent capture bug

Demonstrates a bug in PointerEvent PointerCapture for touch and stylus input where calling setPointerCapture on any element other than the original event target fails to redirect events properly.

## Demonstrations

See https://thatcomputerguy0101.github.io/iOS_pointerCapture_bug/ for the updated demo using regular HTML divs  
See https://thatcomputerguy0101.github.io/iOS_pointerCapture_bug/svg_version.html for the original live demo using SVG groups

#### Explanation

In the new demo, the orange div (the third one) should always track the horizontal movement of the pointer, and the red div (the fourth one) should never, but both will track the movement while the pointer remains over them.
