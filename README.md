# GR-Python — Geodesic Integration Workflows

## Overview

Python notebooks implementing geodesic integration in Schwarzschild and
Kerr spacetimes, built as a self-contained learning workflow before the
KerrWave project. Kept here as reference implementations with more
step-by-step derivation than KerrWave's production code.

## Contents

- `schwarzschild_workflow_full.ipynb` — geodesic equations in
  Schwarzschild spacetime, derived and integrated from scratch
  (effective potential, radial/angular motion, circular photon orbit
  as a sanity check).
- `kerr_metric_workflow.ipynb` — extension to Kerr: metric components,
  constants of motion (E, L_z, Q), and geodesic integration in
  Boyer–Lindquist coordinates.

## Status

Both notebooks are complete and run end-to-end. This repository is kept
as the annotated, step-by-step version of the pipeline later used
(in compiled form) in [KerrWave](https://github.com/juhash/KerrWave).

## Running

Requires `numpy`, `scipy`, `matplotlib`, `jupyter`. Open either notebook
and run all cells top to bottom.
