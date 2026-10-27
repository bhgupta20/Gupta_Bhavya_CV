# Bhavya Gupta — CV

This repository contains the LaTeX source files for my **Curriculum Vitae**.

## Overview
The CV highlights my research experience in **computational astrophysics**, **gravitational-wave data analysis**, and **machine learning for astrophysical inference**.  
It is designed for graduate school, fellowship, and research position applications.

## Repository Structure
- `cv.pdf` — PDF file for the CV
- `cv.tex` — Main LaTeX file for the CV
- `latexmkrc` — Build automation configuration for `latexmk`.
- `README.md` — Repository documentation  

## Compilation
This CV is primarily edited and compiled on [Overleaf](https://www.overleaf.com), where all source files (`.tex`) are stored for easy LaTeX editing.

In addition, a GitHub Actions workflow (`.github/workflows/build_cv.yml`) is set up to automatically compile the CV whenever new changes are pushed to the main branch. The workflow automatically compiles the latest version of the CV (cv.pdf) each time changes are pushed to the main branch. The latest PDF is uploaded directly to the repository, providing an up-to-date version of my CV.
