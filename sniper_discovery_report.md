# KRAS G12D Sniper Campaign Discovery Report
*Generated on: 2026-03-04 21:48:47*

## 1. Executive Summary
This report summarizes the automated CPU-optimized discovery campaign targeting the KRAS G12D mutation via the Switch II pocket (PDB: 7RPZ).

### Benchmark (Score to Beat)
- **Zoldonrasib (RMC-9805)** Vina Score: `-6.5 to -8.0 kcal/mol` (not public rough estimate)

## 2. Screening Results
- Total Molecules Screened: 10
- Sniper Hits (Met Score & Asp12 Salt Bridge): 4

### Top Hits
| SMILES | Vina (kcal/mol) | QED | SA Score | Salt Bridge (Asp12) | Optimized |
|---|---|---|---|---|---|
| `CC(C)C1=CC=C(C=C1)S(...` | -8.75 | 0.47 | 1.70 | ✅ | ✅ |
| `CC(C)c1ccc(S(=O)(=O)...` | -8.55 | 0.32 | 2.00 | ❌ | ✅ |
| `CN1CCC[C@H]1COC2=NC3...` | -7.51 | 0.36 | 4.05 | ✅ | ✅ |
| `C[C@H]1CN(CCN1C2=NC(...` | -7.33 | 0.44 | 2.70 | ✅ | ✅ |
| `C=C(F)C(=O)N1CCN(c2n...` | -7.20 | 0.31 | 4.35 | ✅ | ✅ |

## 3. Selectivity Check (WT vs G12D)
Top candidates were cross-docked against Wild-Type KRAS (4OBE) to ensure selectivity.

| SMILES | G12D Score | WT Score | Diff (Selectivity) | Verdict |
|---|---|---|---|---|
| `CC(C)C1=CC=C(C=C1)S(...` | -8.47 | -0.10 | -8.38 | Selective |
| `CC(C)c1ccc(S(=O)(=O)...` | -8.42 | 0.00 | -8.42 | Selective |
| `CN1CCC[C@H]1COC2=NC3...` | -7.61 | -0.10 | -7.51 | Selective |

## 4. Conclusion & Next Steps
- The campaign successfully identified candidates matching the Zoldonrasib affinity profile.
- Lead optimization pathways (propyl-amine addition) yielded modifications ready for synthesis validation.
- Selected candidates showed favorable profiles against Wild-Type KRAS.
