# GFP Stability Design for SVN Bio-Challenge

This repository contains the designed GFP variants submitted for the competition.

## Files
- `submission.csv` - The 6 final amino acid sequences.
- `设计思路文档.pdf` - Detailed design pipeline, mutant rationale, and selection criteria.

## Design Strategy
- **Template**: PDB 2B3P (sfGFP scaffold, 238 aa).
- **Mutations**: Q69L, S147P, N164Y, T34S (literature-validated thermostability hotspots).
- **Approach**: Gradient combination (double/triple/quadruple mutants) with ESM-IF structure compatibility filtering and fluorescence protection checks (distance to chromophore > 8Å).
- **Output**: 6 sequences with ESM-IF normalized scores ranging from 1.18 to 1.35.

## Environment
No code execution required. All sequences were generated via rational manual design and structural analysis (PyMOL, PyRosetta, ESM-IF API).
