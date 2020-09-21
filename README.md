### iOS PointerEvent capture bug

Demonstrates a bug in PointerEvent PointerCapture for touch and stylus input where calling setPointerCapture on any element other than the original event target fails to redirect events properly.

See https://thatcomputerguy0101.github.io/iOS_pointerCapture_bug/index.html for the original live demo using SVG groups
See https://thatcomputerguy0101.github.io/iOS_pointerCapture_bug/html_version.html for the updated demo using regular HTML divs

In the new demo, the orange div (the third one) should always track the horizontal movement of the pointer, and the red div (the fourth one) should never, but both will track the movement while the pointer remains over them.
