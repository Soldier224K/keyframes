https://github.com/user-attachments/assets/ca5170c7-dc95-4573-9493-ca971f8b6afb

Why does the movement feel so aggressive and heavy?
The animation feels aggressive because you change the coordinates every 1% of the time. This creates a "jittery" zigzag where the light constantly bounces back and forth like a nervous searchlight. It feels heavy because the browser has to recalculate a complex mask-image 100 times every loop, which can strain your computer's processor.

Which keyframe is the most important for the motion? 
The 100% keyframe has the biggest impact. It acts as the "anchor" that brings the light back to the start. Without it, the animation loses its smooth loop; the light would reach the bottom of the screen and then "teleport" or snap instantly back to the top-left corner, creating a jarring visual glitch every 10 seconds.

What would happen to the animation if that keyframe was deleted?
If you removed that final keyframe, the math for the loop would break. The browser wouldn't know how to transition from the 99% position back to the 0% position smoothly. The movement would appear unfinished, and the "flashlight" would seem to disappear and reappear rather than following a continuous, natural path.
