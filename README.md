# Aircraft Boarding and Disembarkation Optimization

This repository contains a comprehensive mathematical analysis of aircraft boarding and disembarkation processes using first-order differential equations and numerical methods.

## Overview

The paper focuses on optimizing the boarding and disembarkation processes for a Boeing 737-800 aircraft with a 3-3 seating configuration. By modeling passenger flow as a continuous fluid system, we analyze different boarding and disembarkation strategies to identify the most efficient approaches.

## Contents

- `complete_paper.tex`: The complete LaTeX document containing the full mathematical analysis
- `main.tex`: First part of the LaTeX document (Sections 1-4)
- `main_part2.tex`: Second part of the LaTeX document (Sections 5-10)
- `boeing737.jpg`: Image of a Boeing 737-800 aircraft used in the paper

## Mathematical Approaches

The paper uses several mathematical techniques:

1. **First-order differential equations** to model passenger flow
2. **Numerical methods** for solving these equations:
   - Euler's method
   - Fourth-order Runge-Kutta method
   - Bernoulli's equation for fluid-like passenger flow

## Boarding Strategies Analyzed

- Back-to-Front boarding
- Outside-In (Window-Middle-Aisle) boarding
- Random boarding
- Proposed optimized hybrid strategy

## Disembarkation Strategies Analyzed

- Front-to-Back disembarkation
- Dual-Door disembarkation
- Priority-Based disembarkation

## Results

Our analysis shows that for a Boeing 737-800 with 126 passengers:

- The back-to-front boarding strategy is theoretically the most efficient (12 minutes)
- The dual-door disembarkation strategy is significantly faster than single-door approaches (6 minutes vs. 10 minutes)
- The optimal combination of strategies could reduce the combined boarding and disembarkation time by up to 17 minutes compared to common current practices

## How to Compile

To compile the LaTeX document, you can use any LaTeX compiler with the necessary packages installed. For example, using pdflatex:

```
pdflatex complete_paper.tex
```

## Citation

If you use this work in your research, please cite it as:

```
Yang, A. (2025). Optimising Passenger Boarding and Disembarkation in Aircraft Through Mathematical Modeling. Mathematics Higher Level Internal Assessment.
```