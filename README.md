# water-benchmarks
Simple Benchmarks of Water Models in LAMMPS

For Reference: Water Gas Phase Dipole Moment $\mu_{gas} = 1.8546 D = 0.286 e\AA$

## Models Considered
1. SPC/E: 3 point tetrahedral water model ($\theta_{HOH}=109.47\degree$).
    - $\mu = 2.35 D = 0.489 e\AA$  (26.7% > $\mu_{gas}$)
    - Center of Charge: $0.289 \AA$ from LJ Center $0.225 \AA$ from CoM
    - LJ $\epsilon$ = 0.1553 kCal/mol; $\sigma$ = 3.166 $\AA$
2. TIP3P/e: 3 point water model with water (bent) geometry ($\theta_{HOH}=104.52\degree$)
    - $\mu = 2.34 D= 0.486 e\AA$ (25.9% > $\mu_{gas}$)
    - Center of Charge: $0.293 \AA$ from LJ Center $0.228 \AA$ from CoM
    - LJ $\epsilon$ = 0.102; $\sigma$ = 3.188 $\AA$
3. TIP4P-Ew: 4 point water model with water (bent) geometry ($\theta_{HOH}=104.52\degree$) & negative charge displaced from O along OH bisector.