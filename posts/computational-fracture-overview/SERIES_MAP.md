# Computational Fracture Series Map

## Recommended site structure

This archive should be treated as a **series**, not as one article.

### Article 1 — Why Is Computational Fracture So Difficult?
**Role:** overview / gateway article  
**Core papers:** ZiBel03, Bel..03, Zi..04, Zi..05, RabZi07, Zi..07b, Rab..07b, Rab..10  
**Question:** How can a numerical approximation represent a discontinuity that moves independently of the discretization?

### Article 2 — How Does XFEM Let a Crack Cut Through the Mesh?
**Core papers:** ZiBel03, Bel..03, Zi..04, Bud..04, Lee..04, Zi..05  
**Themes:** local partition of unity; jump enrichment; crack-tip elements; cohesive cracks; level sets; dynamic fracture; multiple cracks; crack junction/coalescence; superimposed finite elements.

### Article 3 — Why Did We Extend XFEM into Meshfree Methods?
**Core papers:** RabZi07, Zi..07b, Rab..07b, Bor..08, Rab..10  
**Themes:** XEFG; particle support domains; complete/partial cuts; branch enrichment; cohesive crack closure; static and dynamic fracture; 3D crack surfaces and junctions.

### Article 4 — How Do Multiple Cracks Branch, Join, and Form a Fracture Network?
**Core papers:** Zi..04, Bud..04, Bel..03, Rab..07b, Bor..08, Rab..10  
**Themes:** multiple crack growth; fatigue; competitive crack tips; branching; junctions; coalescence; topology evolution; 3D crack tracking.

### Article 5 — Is Enrichment the Only Way to Represent a Crack?
**Core papers:** Rab..08, Cha..12, VuB..13, Cha..18, Rab..10b, Ama..16, Mse..16, Mse..18  
**Themes:** phantom-node method; cracked shell elements; cracking-particle methods; peridynamics; phase-field fracture; sharp vs diffuse discontinuities.

### Article 6 — How Does Computational Fracture Move Across Scales and Structural Forms?
**Core papers:** Rab..08b, Ngu..12, Tal..12, Ngu..15, Sil..15, Yan..15, Bud..15, Bud..16, Mse..16, Mse..18  
**Themes:** reinforced concrete; piezoelectric materials; shells; multiscale coupling; atomistics; graphene; nanocomposites.

### Possible Article 7 — What Did Enriched Methods Teach Us About Computational Mechanics?
**Role:** retrospective synthesis  
**Source base:** entire archive, especially Rab..14 editorial and the progression from XFEM/XEFG to later methods.  
**Themes:** approximation space vs mesh; prior information; geometry-independent discretization; trade-offs between sharp enrichment and alternative fracture representations.

---

## Paper classification

| File | Main role in series |
|---|---|
| `ZiBel03.pdf` | Core XFEM; new crack-tip elements for cohesive cracks |
| `Bel..03.pdf` | Dynamic propagation; loss of hyperbolicity; discontinuous enrichment |
| `Zi..04.pdf` | Multiple cracks; fatigue crack growth; no remeshing |
| `Bud..04.pdf` | Multiple crack growth, coalescence, percolation |
| `Lee..04.pdf` | XFEM + superimposed FEM; stationary/growing cracks |
| `Zi..05.pdf` | Dynamic XFEM; level sets; arbitrary crack paths |
| `RabZi07.pdf` | XEFG foundation for cohesive cracks |
| `Zi..07b.pdf` | XEFG without branch enrichment |
| `Rab..07b.pdf` | 3D XEFG; initiation, propagation, junction |
| `Bor..08.pdf` | 3D XEFG; branching/junction without asymptotic enrichment |
| `Rab..08.pdf` | Phantom-node crack-tip element |
| `Rab..08b.pdf` | Geometrically nonlinear 3D cohesive cracks in reinforced concrete |
| `Rab..10.pdf` | 3D crack tracking with partition-of-unity/XEFG |
| `Rab..10b.pdf` | Cracking-particle method without enrichment |
| `Cha..12.pdf` | Phantom-node shell elements with arbitrary cracks |
| `Tal..12.pdf` | Multilevel FE / computational homogenization |
| `Ngu..12.pdf` | XFEM for dynamic fracture of piezoelectric materials |
| `VuB..13.pdf` | Phantom-node + edge-based strain smoothing |
| `Rab..14.pdf` | Editorial perspective on computational fracture |
| `Sil..15.pdf` | 3D extended Arlequin multiscale dynamic fracture |
| `Yan..15.pdf` | Adaptive meshless multiscale fracture |
| `Ngu..15.pdf` | Extended isogeometric thin-shell analysis with cracks |
| `Bud..15.pdf` | Crack propagation in graphene |
| `Bud..16.pdf` | Graphene lattice orientation and crack-size effects |
| `Ama..16.pdf` | State-based peridynamics for thermoplastic fracture |
| `Mse..16.pdf` | Phase-field fracture of clay/epoxy nanocomposites |
| `Cha..18.pdf` | Phantom-node MITC4 shells and fracture parameters |
| `Mse..18.pdf` | Phase-field nanocomposites with interphase zones |

## Recommended publishing order

1. Overview
2. XFEM mechanics
3. XEFG mechanics
4. Multiple cracks / branching / 3D topology
5. Alternative representations
6. Multiscale and applications
7. Retrospective synthesis, if desired

This order follows the engineering ideas rather than publication chronology.
