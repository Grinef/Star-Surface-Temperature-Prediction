# Star Surface Temperature Prediction

## Project Overview
The observatory "Sky in Your Palm" has tasked us with developing a neural network to determine the surface temperature of newly discovered stars. Traditional methods like Wien's displacement law, the Stefan-Boltzmann law, and spectral analysis each have their pros and cons. The observatory aims to integrate machine learning technologies for predicting star temperatures, expecting this method to be more accurate and convenient.

The observatory's database contains characteristics of 240 well-studied stars. This project involves developing a neural network model to predict the absolute surface temperature of stars.

## Star Characteristics
The dataset contains the following characteristics for each star:

- **Relative Luminosity (L/Lo)**: The star's luminosity relative to the Sun.
- **Relative Radius (R/Ro)**: The star's radius relative to the Sun's radius.
- **Absolute Magnitude (Mv)**: A physical quantity characterizing the star's brightness.
- **Star Color**: The star's color, determined through spectral analysis (e.g., white, red, blue, yellow, yellow-orange).
- **Star Type**:
  - Brown Dwarf: 0
  - Red Dwarf: 1
  - White Dwarf: 2
  - Main Sequence Star: 3
  - Supergiant: 4
  - Hypergiant: 5
- **Absolute Temperature (T(K))**: The star's surface temperature in Kelvins.
