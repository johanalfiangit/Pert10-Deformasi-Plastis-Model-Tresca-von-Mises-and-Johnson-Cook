# Pert10-Deformasi-Plastis-Model-Tresca-von-Mises-and-Johnson-Cook
Tresca yield criterion, von Mises criterion, Johnson–Cook constitutive model, modified Johnson–Cook formulation,
# Metal Forming Calculator

### Interactive Engineering Calculator for Metal Forming and Material Mechanics

An interactive web-based engineering calculator developed to support learning and analysis in manufacturing engineering, particularly metal forming, plastic deformation, and material constitutive modeling.

## Overview

This application integrates several mathematical models used in material mechanics and manufacturing engineering:

1. Tresca Yield Criterion
2. von Mises Yield Criterion
3. Standard Johnson–Cook Constitutive Model
4. Modified Johnson–Cook Constitutive Model
5. Strain Hardening Analysis
6. Strain-Rate Sensitivity Analysis
7. Thermal Softening Analysis

The application provides automatic calculations, interactive engineering graphs, and downloadable calculation reports in PDF format.

## Key Features

- Editable material and process parameters.
- Automatic calculation of equivalent stress.
- Tresca and von Mises yield assessment.
- Johnson–Cook flow stress prediction.
- Modified Johnson–Cook formulation.
- Interactive stress–strain visualization.
- Strain-rate and temperature response graphs.
- Automatic calculation summary.
- CSV data export.
- PDF report generation through browser print functionality.
- Responsive interface for desktop and mobile devices.

## Material Case Study

**Material:** ADC12 Aluminium Alloy

**Manufacturing Process:** High-Speed Milling

The default material parameters are based on:

Meng, X., Lin, Y., & Mi, S. (2020). An Improved Johnson–Cook Constitutive Model and Its Experiment Validation on Cutting Force of ADC12 Aluminum Alloy During High-Speed Milling. *Metals, 10*(8), 1038.

https://doi.org/10.3390/met10081038

## Mathematical Models

### 1. Tresca Yield Criterion

τ_max = (σ₁ − σ₃) / 2

Yield condition:

τ_max ≥ σ_y / 2

### 2. von Mises Criterion

σ_VM = √{[(σ₁−σ₂)² + (σ₂−σ₃)² + (σ₃−σ₁)²]/2}

Yield condition:

σ_VM ≥ σ_y

### 3. Standard Johnson–Cook Model

σ = (A + Bεₚⁿ)[1 + C ln(ε̇/ε̇₀)][1 − (T*)ᵐ]

Where:

- A = Initial yield stress
- B = Strain hardening coefficient
- n = Strain hardening exponent
- C = Strain-rate sensitivity coefficient
- m = Thermal softening exponent
- εₚ = Equivalent plastic strain
- ε̇ = Plastic strain rate
- T* = Homologous temperature

## Technology Stack

- HTML5
- CSS3
- JavaScript
- SVG-based interactive charts
- Browser-based PDF export
- CSV export

No backend installation is required.

## How to Use

1. Download or clone this repository.
2. Open `Kalkulator_Tresca_vonMises_JohnsonCook_ADC12.html` in a modern web browser.
3. Modify material and process parameters.
4. Recalculate the engineering models.
5. Analyze the interactive graphs and calculation results.
6. Export the results to PDF or CSV.

## Intended Applications

- Manufacturing Engineering Education
- Metal Forming Analysis
- Plastic Deformation Mechanics
- Material Yield Analysis
- Constitutive Material Modeling
- Engineering Simulation Learning
- High-Speed Machining Analysis

## Scientific Reference

Meng, X., Lin, Y., & Mi, S. (2020). An Improved Johnson–Cook Constitutive Model and Its Experiment Validation on Cutting Force of ADC12 Aluminum Alloy During High-Speed Milling. *Metals, 10*(8), 1038.

https://doi.org/10.3390/met10081038

## Disclaimer

This calculator is intended for educational and preliminary engineering analysis. Numerical outputs depend on user-defined inputs and the validity range of the selected constitutive model. The Tresca and von Mises modules are supplementary yield-analysis tools and are not presented as experimental findings of the referenced ADC12 study.

## License

MIT License (recommended, subject to repository owner's approval).
