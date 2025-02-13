## Density of States (DOS) for Graphene Nanoribbons

This project calculates the Density of States (DOS) for graphene nanoribbons using a tight-binding model. The code supports both zigzag and armchair nanoribbons and allows for the substitution of carbon atoms with silicon to study the effect of doping on the electronic structure.

## Introduction

Graphene nanoribbons are one-dimensional structures of graphene with unique electronic properties that depend on their edge geometry (zigzag or armchair). This project uses a tight-binding Hamiltonian to model the electronic structure of graphene nanoribbons and calculates the Density of States (DOS) for both pure carbon systems and systems with silicon doping.

The code provides:

A lattice generator for zigzag and armchair nanoribbons.

A tight-binding Hamiltonian constructor with support for silicon doping.

A Green's function-based method to calculate the DOS.

Visualization of the DOS for both carbon and silicon-doped systems.

## Features

Lattice Generation: Generates atomic positions for zigzag and armchair graphene nanoribbons.

Tight-Binding Hamiltonian: Constructs the Hamiltonian matrix for the system, with optional silicon doping.

Density of States (DOS) Calculation: Uses the Green's function method to compute the DOS.

Visualization: Plots the DOS for both carbon and silicon-doped systems.

## Results

The script generates plots of the Density of States (DOS) for both zigzag and armchair graphene nanoribbons, comparing the pure carbon system with the silicon-doped system.

Example Outputs:

Zigzag Nanoribbon:

-DOS for pure carbon (C) and silicon-doped (C-Si) systems.

-Plot of DOS vs. energy for the zigzag configuration.

Armchair Nanoribbon:

-DOS for pure carbon (C) and silicon-doped (C-Si) systems.

-Plot of DOS vs. energy for the armchair configuration.

## Dependencies

NumPy: A fundamental package for scientific computing with Python.

Matplotlib: A plotting library for creating static, animated, and interactive visualizations.

SciPy: A library for scientific and technical computing, used here for linear algebra operations.

## Installation

To run this project, you need to have Python installed along with the required libraries. You can install the dependencies using the following commands:

pip install numpy matplotlib scipy!
