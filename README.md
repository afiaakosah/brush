# Brush Project

A painting application that features multiple types of brushes that you can use to paint on a 2D canvas, similar to applications such as MS Paint and Photoshop. All of the brushes are implemented using masks.

## Brushes
1. Constant: equal amount of color at each pixel within the brush's radius.

2. Linear: linearly decreasing amount of color at each pixel as you move away from the center point. The amount of color at the center point is 1, and the amount of color at the edge is 0. 

3. Quadratic: quadratically decreasing amount of color at each pixel as you move away from the center point.

4. Smudge: creates a smear effect by repeatedly "picking up" and "putting down" color when you click and drag the mouse across the canvas.

