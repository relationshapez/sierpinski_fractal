# Relationshapez: Sierpinski Triangle

This project is a single-file, mobile-friendly HTML exploration of the Sierpinski triangle. It is designed for classroom demonstrations, student exploration, and quick use on phones, tablets, or computers.

<https://relationshapez.github.io/sierpinski_fractal/>

## Files

- `index.html` — the main interactive browser tool
- `README.md` — repository overview and usage guide
- `LICENSE` — MIT license text

## How to Use

Open `index.html` in a web browser.

The app begins with a solid triangle at iteration 0. Each new iteration removes the middle triangle from every remaining triangle, producing the familiar Sierpinski triangle pattern.

### Controls

- **Animate** starts the stage-by-stage construction.
- **Pause** stops the animation at the current iteration.
- **Reset** returns to iteration 0 and resets the view.
- **◀** moves backward one iteration when the animation is paused.
- **▶** moves forward one iteration when the animation is paused.
- **Max** sets the maximum number of iterations shown. The app allows up to 12 iterations. Higher values create much more detail, but they may render more slowly on phones or older devices.
- **Speed** changes the animation speed.

At the lowest speed setting, the app highlights the outline of the middle triangle being removed and then fades it out before moving to the next iteration.

Because the number of visible pieces grows quickly, iterations 10–12 may take noticeably longer to draw on some mobile devices.

## Zooming and Panning

The drawing area supports zooming and panning.

- On a trackpad or mouse, scroll to zoom and drag to pan.
- On a touchscreen, drag to pan and pinch to zoom.

Zooming and panning do not reset when the animation resumes. The view only returns to the original centered view when **Reset** is pressed.

## Classroom Notes

The Sierpinski triangle is a good example of how a simple repeated rule can produce a complicated-looking shape. At each iteration:

1. Start with every filled triangle from the previous stage.
2. Divide each triangle into four congruent smaller triangles.
3. Remove the middle triangle.
4. Repeat.

This makes the app useful for discussing recursion, self-similarity, fractals, powers of 3, and geometric limits.

## License

Copyright (c) 2026 Alan Miller.

This project is released under the **MIT License**.

See the [`LICENSE`](LICENSE) file for the full license text.
