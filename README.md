# JuliaOpt Notebooks

![Julia](https://img.shields.io/badge/Julia-9558B2?style=flat-square&logo=julia&logoColor=white)
![Jupyter](https://img.shields.io/badge/Jupyter-F37626?style=flat-square&logo=jupyter&logoColor=white)
![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg?style=flat-square)

> **Note:** This repository is a fork of [JuliaOpt/juliaopt-notebooks](https://github.com/JuliaOpt/juliaopt-notebooks).

A collection of Jupyter (IJulia) notebooks demonstrating optimization techniques and mathematical programming in Julia using the JuMP modeling framework.

## Overview

This repository contains a curated set of Jupyter notebooks that showcase various optimization problems and solution methods implemented in Julia. Topics range from introductory linear programming to advanced techniques such as Benders decomposition, column generation, and sensitivity analysis. The notebooks leverage the JuMP ecosystem for mathematical optimization modeling.

## Features

- **JuMP Modeling Examples:** Rocket trajectory optimization, revenue management, Chebyshev center, Sudoku solver, and more
- **Decomposition Methods:** Benders decomposition and column generation
- **Sensitivity Analysis:** Post-optimality analysis with JuMP
- **Convex Optimization:** Matrix completion and sparse optimization
- **Power Systems:** Economic dispatch and unit commitment models
- **Dual Numbers:** Automatic differentiation with dual numbers
- **MathProgBase:** Custom Newton solver implementation

## Prerequisites

- [Julia](https://julialang.org/downloads/) (1.0 or higher recommended)
- [IJulia](https://github.com/JuliaInteractive/IJulia.jl) kernel for Jupyter
- [JuMP](https://jump.dev/) and associated solver packages

## Getting Started

### Installation

Clone the repository:

```bash
git clone https://github.com/danielcregg/juliaopt-notebooks.git
cd juliaopt-notebooks
```

Install Julia dependencies:

```julia
using Pkg
Pkg.add("IJulia")
Pkg.add("JuMP")
```

### Usage

Launch Jupyter Notebook and open any notebook from the `notebooks/` directory:

```bash
jupyter notebook notebooks/
```

Alternatively, you can launch directly in Binder:

[![Binder](https://mybinder.org/badge_logo.svg)](https://mybinder.org/v2/gh/danielcregg/juliaopt-notebooks/master)

Or view the notebooks online via [NBViewer](http://nbviewer.ipython.org/github/JuliaOpt/juliaopt-notebooks/tree/master/notebooks/).

## Tech Stack

- **Language:** Julia
- **Optimization Framework:** JuMP / MathProgBase
- **Notebook Environment:** Jupyter (IJulia)

## License

This project is licensed under the MIT License. See the [LICENSE](LICENSE) file for details.
