# aerodynamics-cfd-harpoon-analysis
Computational fluid dynamics (CFD) study of an external-store geometry under compressible/incompressible viscous flow assumptions (Aerodynamics-II final report).
# Aerodynamics CFD – Harpoon External Store Analysis
# AGM-84 Harpoon Aerodynamic Flow Analysis (CFD) — Aerodynamics II Final

This repository contains my **Aerodynamics-II final assignment** on the CFD investigation of the **AGM-84 Harpoon** missile’s external aerodynamics under **viscous compressible / incompressible** flow assumptions.

## Objective
- Investigate the turbulent flow field around the missile geometry
- Evaluate **pressure distribution** and aerodynamic performance indicators such as:
  - **Drag / Lift**
  - **Aerodynamic coefficients (CL, CD, etc.)**
- Support the discussion with a clear CFD methodology (domain, BCs, model choice)

## Methodology (high-level)
- **Solver/Tool:** ANSYS **Fluent** (external flow / enclosure domain)
- **Turbulence modeling:** RANS approach (the report lists multiple turbulence models and explains the selected one in detail)
- **Control volume / domain (enclosure):**
  - Rectangular box enclosure created around the missile
  - Upstream distance extended more in the **negative X direction** (report uses a non-uniform domain)
  - Far-field boundaries are set as **symmetry** (not “wall”) to mimic free-stream conditions
- **Deliverables in the report:**
  - Turbulence model equations + constants/variables
  - Control-volume sketch + boundary conditions table
  - Step-by-step CFD workflow and assumptions

## Files
- **Full report (PDF):** `docs/agm84-harpoon-cfd-report.pdf`

## Notes (portfolio / privacy)
This report includes a cover page with personal/course identifiers.  
If you plan to keep the repository **Public**, consider uploading a **redacted PDF** (cover page removed) for privacy.

---
**Course:** Aerodynamics-II (Final Assignment)  
**Topic:** AGM-84 Harpoon CFD / viscous compressible–incompressible flow analysis
