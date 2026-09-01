# membrane-sandwich-


![til](./mem05_r5uma_ospacat_opc.gif)

Movie 1: A penta(arginine) undecyl-spaced methylenetriazyl methacrylate (R5uMA) in presence of a DOPE/DOPG 3/1 lipid bilayer. The trajectory covers 12.5 ns in the NPT (with a Berendsen barostat and a Beredenthermostat (ntt=1) at 300 K and 1 bar. Non-peptidic content is parametrised against gaff2, amino acids against ff14SB. The water model is the optimal point charge (OPC) scheme. K+ (not rendered) are added to neutralise the phosphate esters of DOPG and do not stay condensed to the membrane (physically correct behaviour). Cl- do not appear condensed to R5uMA.

The membrane moves considerably, which could be due to a local transmembrane osmotic pressure gradient (R5uMA is present on only one side), or to insufficient optimisation in the pre-production phase (5x10000 cycles followed by heating in NVT, NPT, and then a 1 ns run in the NPT). Either way it is worthwhile to continue the simulation, re-center the membrane, and potentially demarcate a second production phase. This movement is completely absent from trajectories generated from membrane-only simulations (Movie 2, the comparison is nevertheless partial, since the box dimensions are slightly smaller).

[!til](./mem03-prod_25ns_2.gif)

Movie 2: Bilayer-only trajectory (25 ns) in OPC water. Purple spheres are phosphatidylglyceryl moities (they are covalently bound to the lipids), red spheres are K+ ions.

