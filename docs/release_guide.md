# Release Guide

This guide describes how to update the initial CAR-VLA repository as the paper and code become available.

## Paper link

The paper is available at [arXiv:2609.34387](https://arxiv.org/abs/2609.34387). The README badge, paper links, and BibTeX entry use this identifier. The arXiv item in the **Todo List** is complete.

The links omit a version suffix so that they open the latest arXiv version. When publication metadata changes, update the **Paper**, **News**, and **Citation** sections together.

## Release the implementation

1. Populate `car_vla/`, `configs/`, and `scripts/` with the cleaned implementation.
2. Add tested dependencies, environment setup, data preparation, and reproducible training and evaluation commands.
3. Select the repository license and retain the licenses and notices required by any included upstream code.
4. Update the directory documentation, **News**, **Todo List**, and code status badge to reflect what is actually available.

## Figure asset

`assets/car-vla-mascot.png` is the original project mascot image, displayed to the left of the CAR-VLA title in the README.

`assets/method.pdf` is the paper's method overview, sourced from `overleaf/figures/overview_final_v6.pdf`. `assets/method.png` is a 3200-pixel-wide rendering used in the README so that GitHub displays the figure inline. Keep both files in sync when updating the figure.
