# Example of estimating absolute protein concentrations in a quantitative western blot

Western blot fluorescence is a hyperbolic function of molar protein concentration (https://www.science.org/doi/full/10.1126/scisignal.2005966). As a result, a curve can be fit to protein standards and used to estimate the amount of protein in a band of unknown concentration.

This Jupyter notebook is an example of how to take the raw fluorescence values from a quantitative western blot into an estimate of absolute protein concentrations for the standards and test samples.

In reality, the curve is probably also affected by protein size but there is no literature on this to my knowledge.