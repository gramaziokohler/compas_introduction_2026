# COMPAS Introduction: MAS 2026/2027

[🎦 Introduction slides (2025 reference)](https://docs.google.com/presentation/d/1Sv9Yyys9Ud5o9Huc6GJtrD2rFueIHChBNAs1Dag9dQo/edit?usp=sharing)

## Setup

Use Rhino 8 with its Python 3 components. The examples use the `ca-hs26` script environment and COMPAS 2.15.1 or newer (below 3 for the VS Code environment), following the [HS26 teaching material](https://github.com/gramaziokohler/coding_architecture_hs26_teaching). See the [installation guide](https://github.com/gramaziokohler/coding_architecture_hs26_teaching/blob/main/getting-started/README.md) and [VS Code setup](./using-vscode/README.md).

## Examples

* [Hello world](./examples/00_hello_world.gh)
* [Anatomy of code](./examples/01_anatomy_of_code_hs26.gh)
* [Grasshopper Python Basics](./examples/02-grasshopper-python-basics-iii_hs26.gh)
* [3D Grids and Filters](./examples/03-3d-grids-and-filters_hs26.gh)
* [Math in Python](./examples/math-in-python.md)

## Exercise

Write a brick wall in Python! 

* 2D grid of bricks (stretcher bond)
* **Inputs:** brick dimensions (x, y, z), row and column count
* **Output:** list of bricks (COMPAS boxes)
* Add a Draw component to visualize
* Bonus 1: Attractor point to control each brick’s rotation
* Bonus 2: Half-bricks to have flushed ends

Use the following file as a starting point: [`/exercise/brick_wall.gh`](./exercise/brick_wall.gh).

## Using VS Code

How to setup your VS Code editor to write Python code outside Rhino. See example in [`/using-vscode`](./using-vscode/).

## Roadmap

See [`here`](./roadmap/README.md) for the Roadmap: becoming a computational designer, that provides guidance during the learning process and helps you understand how much you've progressed and what are the skills and concepts that you should master in order to move forward.

## Sources and license

This is an independent repository adapted from [COMPAS Introduction 2025](https://github.com/gramaziokohler/compas_introduction_2025), with environments and setup updated from [Coding Architecture HS26](https://github.com/gramaziokohler/coding_architecture_hs26_teaching). The original lesson sequence, exercises, and supporting material are retained. See [migration notes](./MIGRATION.md) and [LICENSE](./LICENSE).
