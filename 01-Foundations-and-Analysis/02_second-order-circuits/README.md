# Second-Order Circuits

## Overview

This section explores the transient behavior of second-order RLC circuits using LTspice. Both series and parallel configurations are investigated to understand their natural and step responses, damping characteristics, and energy-storage behavior.

## Experiments

### 1. Series RLC Circuit

- Investigated the step response of a series RLC circuit.
- Observed capacitor voltage and inductor current during source ON and OFF intervals.
- Calculated the damping factor and undamped natural frequency.
- Identified the overdamped response and examined its exponential decay.

### 2. Parallel RLC Circuit

- Investigated the step response of a parallel RLC circuit.
- Observed capacitor voltage and inductor current during source ON and OFF intervals.
- Calculated the damping factor and undamped natural frequency.
- Examined the source-free response and its overdamped behavior.

## Theoretical Background

Second-order RLC circuits contain two independent energy-storage elements: a capacitor and an inductor.

Their transient responses are governed by second-order differential equations. Depending on the circuit configuration and component values, the natural response can be classified as:

- **Underdamped:** Oscillatory response with exponentially decreasing amplitude.
- **Critically damped:** Fastest non-oscillatory natural response.
- **Overdamped:** Non-oscillatory response consisting of two decaying exponential terms.

The damping factor and undamped natural frequency determine the response characteristics.

### Series RLC

\[
\alpha = \frac{R}{2L}
\]

\[
\omega_0 = \frac{1}{\sqrt{LC}}
\]

### Parallel RLC

\[
\alpha = \frac{1}{2RC}
\]

\[
\omega_0 = \frac{1}{\sqrt{LC}}
\]

## Objectives

- Understand second-order transient circuit behavior.
- Compare series and parallel RLC configurations.
- Investigate natural and step responses.
- Understand underdamped, critically damped, and overdamped conditions.
- Examine the influence of resistance, inductance, and capacitance on circuit response.
- Verify theoretical predictions through LTspice simulations.

## Tools

- LTspice