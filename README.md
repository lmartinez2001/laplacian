# Experiments with Laplacian operator

This repo aims to play arounf with the Laplacian operator. The idea of making it comes from a [X post](https://x.com/gabrielpeyre/status/1884481605089255549) from Gabriel Peyré.  
For short, the Laplacian is a differential operator which appears in the modelling of many physical phenomena. Here is a list (from ChatGPT) of some of them:
- Heat Diffusion
- Wave Propagation
- Electrostatics
- Quantum Mechanics
- ...

Eventually, this repo will propose some numerical simulations for most of these phenomena, but there's no guarantee.

Before we delve into the mess that is numerical simulation, let's first define the mathematical objects we're going to use:

NOTATIONS

## Spectral Decomposition

In many cases, the differential equations we'll be simulating can be efficiently solved using the spectral decomposition of the Laplacian operator. Whenever necessary, we'll explain how this decomposition facilitates the solution of these equations.  
Let's first explain how spectral decomposition works. A key element to keep in mind is that the Laplacian is a Linear operator mapping a scalar field to another scalar field. It can thus be represented as a matrix.

REST OF THE EXPLANATIONS

<p align="center">
  <img src="images/france.gif" alt="France" width="300">
  <img src="images/horse.gif" alt="Horse" width="300">
</p>
