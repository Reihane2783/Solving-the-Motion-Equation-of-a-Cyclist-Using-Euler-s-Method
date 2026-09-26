# Bicycling Motion Simulation Using Euler's Method

A Python-based numerical simulation of a cyclist's motion using the first-order Euler method, with and without air resistance.

## Overview

This project models the time evolution of a cyclist's velocity under a constant power output.

Two cases are compared:

- Bicycling without air resistance
- Bicycling with aerodynamic drag

The simulation demonstrates how air resistance affects the velocity of a cyclist over time.

## Physical Model

The cyclist's acceleration is determined from the applied power and the resistive drag force.

The aerodynamic drag is modeled using the cyclist's drag coefficient, air density, frontal area, and velocity.

## Numerical Method

The equations of motion are solved using the first-order Euler method with a fixed time step.

The velocity is updated at each time step and the resulting velocity-time curves are compared for the two cases.

## Simulation Parameters

- Initial velocity: `4 m/s`
- Power: `400 W`
- Mass: `70 kg`
- Drag coefficient: `0.5`
- Air density: `1 kg/m³`
- Frontal area: `0.33 m²`
- Time step: `0.1 s`
- Total simulation time: `200 s`

## Visualization

The generated plot compares:

- Velocity without air resistance
- Velocity with air resistance

This illustrates the significant effect of aerodynamic drag on the cyclist's motion.

## Scientific Concepts

- Classical mechanics
- Numerical integration
- Euler's method
- Power and velocity
- Aerodynamic drag
- Computational physics

## Technologies

- Python
- NumPy
- Matplotlib
