# Bayesian Reconstruction of Partially Observed Tongue Shapes

## Overview

The aim of this project is to use Bayesian methods to reconstruct full tongue shapes from partially observed shapes. The data originate from magnetic resonance imaging and represent tongue shapes as two-dimensional curves, described by their x- and y-coordinates. The project models the curve coordinates using polynomials, specifically normalised shifted Legendre polynomials.

The work considers modelling the partially observed curves as a linear combination of the existing fully observed curves, as well as a principal component analysis (PCA)-based extension of this approach. For both approaches, the curve coordinates are modelled separately and jointly, with the latter allowing for dependence between the x- and y-coordinates. The different approaches are compared numerically using absolute prediction errors through a cross-validation-based procedure.

## Project

The project is available in the form of a poster [here](Poster.pdf).

The R Markdown code is available [here](Bayesian%20Reconstruction%20of%20Partially%20Observed%20Tongue%20Shapes.Rmd).

