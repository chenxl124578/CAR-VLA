# Release Guide

This guide describes how to update the initial CAR-VLA repository as the paper and code become available.

## Add the arXiv link

1. Open the root `README.md` and search for `ARXIV_URL`.
2. In the following `<a>` tag, replace `href="#paper"` with the actual arXiv abstract URL, for example `https://arxiv.org/abs/YOUR_PAPER_ID`.
3. In that badge's image URL, replace `coming%20soon` with the paper identifier, and update its alt text.
4. Replace the placeholder sentence in the **Paper** section with the paper link.
5. Update the BibTeX entry with the official arXiv metadata and mark the arXiv item in the **Todo List** complete.

## Release the implementation

1. Populate `car_vla/`, `configs/`, and `scripts/` with the cleaned implementation.
2. Add tested dependencies, environment setup, data preparation, and reproducible training and evaluation commands.
3. Select the repository license and retain the licenses and notices required by any included upstream code.
4. Update the directory documentation, **News**, **Todo List**, and code status badge to reflect what is actually available.

## Figure asset

`assets/method.pdf` is the paper's method overview, sourced from `overleaf/figures/overview_final_v6.pdf`. `assets/method.png` is a 3200-pixel-wide rendering used in the README so that GitHub displays the figure inline. Keep both files in sync when updating the figure.
