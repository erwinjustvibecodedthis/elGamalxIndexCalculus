# Index Calculus vs El Gamal

This repository contains a Jython-compatible implementation and supporting code for ElGamal and Index Calculus code used in my project.

Goals of this restructure
- Normalize layout to a standard Python packaging layout (src/).
- Add a minimal test harness and CI for reproducible validation.
- Provide packaging metadata (pyproject + setup.py).
- Keep code modular and import-friendly for Jython/CPython environments.

Quickstart (local)
1. Create a virtualenv with a Python implementation:
   - For CPython:
     python3 -m venv .venv
     source .venv/bin/activate
     pip install -e .
     pip install -r requirements-dev.txt  # if provided
   - For Jython:
     Install Jython (see Jython docs) and use the corresponding pip for Jython.

2. Run tests:
   pytest

Notes
- This project aims for compatibility with Jython 2.7.x. Some modern Python 3-only syntax may need adjustments before using under Jython.
- If you want, I can open a branch, push these changes, and optionally add a Jython-based CI job after you confirm your preferred Jython version.
