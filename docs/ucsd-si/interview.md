# Math 20B Supplemental Instruction Week 2

Welcome to Week 2 of Math 20B SI sessions! Today we'll be covering solids of revolution.

This webpage will always be available to you, so if you come in late or have to leave early, or we don't get through all the practice problems, you can access them 

You can submit anonymous questions to me any time during the SI session using the link [here](https://forms.gle/DP6pPRdmFoGrqPk88). Or, feel free to unmute yourself and ask questions or type them in the chat at any time!

## Mini-Review: Integration

## Mini-Review: Solids of Revolution
A solid of revolution is any 3-dimensional solid created by revolving a 2-dimensional plane figure about a line in the plane. Let's visualize one, specifically $f(x)=x^2$!

<iframe src="https://www.geogebra.org/classic/v5c6n7rs" style="width: 900px; height: 750px; border: 0px"></iframe>

[Here](https://www.geogebra.org/classic/v5c6n7rs) is a link to the visual in case the embedded version doesn't work. You can drag the slider of the angle and pan the camera to visualize the full graph.

We're interested in finding the volume of a solid of revolution. The general formula for this volume is listed below.  

$V = \int_a^b\pi\left[f(x)\right]^2\mathrm{d}x$

$f(x)$ is the function that determines how the radius of the solid we're looking at changes as we move along its height. What formula does this volume formula remind you of?

This method of finding the volume is called the disk method, because we're basically adding up a bunch of disks that make up the volume of the entire solid.

So, we just plug in the function, the bounds, and we can evaluate the volume.
$V = \int_a^b\pi\left[f(x)\right]^2\mathrm{d}x$
$V = \int_{-2}^{2}\pi\left[x^2]^2\mathrm{d}x$
$V = \pi\int_{-2}^{2}x^4\mathrm{d}x$
$V = \frac{x^5}{5}\left.\right|^2_{-2}$
$V = \frac{2^5}{5} - \frac{(-2)^5}{5}$
$V = \frac{64}{5}$

<details>
  <summary>Click me</summary>
  
  ### Heading
  1. Foo
  2. Bar
     * Baz
     * Qux

  ### Some Javascript
  ```js
  function logSomething(something) {
    console.log('Something', something);
  }
  ```
</details>

## Example
![example](../images/ucsd-si/interview/example.png)
Let's visualize the solid created first.

## Problem 1
![example](../images/ucsd-si/interview/problem1.png)
Work through
## Problem 2
![example](../images/ucsd-si/interview/problem2.png)

## Problem 3
![example](../images/ucsd-si/interview/problem3.png)
