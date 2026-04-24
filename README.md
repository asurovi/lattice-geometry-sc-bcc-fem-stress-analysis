# Finite Element Comparison of Simple Cubic and Body-Centered Lattice Structures

This project compares the mechanical response of two lattice unit-cell geometries — Simple Cubic (SC) and Body-Centered Cubic (BCC) — using finite element simulations under compression (5% strain).

## Motivation
Lattice geometry plays a critical role in determining how loads are distributed in lightweight and porous structures. Understanding this behavior is important for applications such as additive manufacturing and biomedical scaffolds.

## Key Observation
- Simple Cubic (SC): Stress localizes primarily in vertical members  
- Body-Centered Cubic (BCC): Multiple diagonal load paths distribute stress more uniformly  

## Takeaway
Even with identical material properties, **geometry (topology) significantly influences stress distribution and load transfer behavior**.

## Repository Structure
- `models/` → Geometry files (STL/STEP)  
- `abaqus/` → Input files for simulations  
- `results/figures/` → Geometry, stress plots and comparison figures
- `results/data/` → Stress data and comparison plot
- `docs/` → a presentation with references 

## Note
Due to file size limitations, some Abaqus input files may be provided via google drive.

## How to Use

1. Open `.inp` files in Abaqus
2. Run compression simulations (5% strain)
3. Post-process results for stress distribution

---

This work was developed as part of graduate study in additive manufacturing (ME569), focusing on simulation-driven design of lattice structures.
