# Crossword — CSP Crossword Generator and Solver

Generate and solve crosswords using constraint satisfaction techniques.

**Overview**
- `generate.py` creates a filled crossword from a structure file and a word list.

**Requirements**
- Python 3.6+
- `Pillow` for image export (optional)

**Quick Start**
```bash
cd crossword
python generate.py structure0.txt words0.txt output.png
```

**Files**
- `crossword.py` — crossword representation and variable detection.
- `generate.py` — CSP solver, AC-3 and backtracking search, image export.
