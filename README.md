# ML-Enhanced Self-Powered Thermal Sensing: Data & Validation

Supplementary data and validation files for the paper:

**Machine Learning-Enhanced Self-Powered Thermal Sensing Based on Piezoelectric–Thermoelectric Hybrid Energy Harvesting**

## Tables
| File | Content | Paper Section |
|------|---------|---------------|
| table1_material_properties.csv | PZT-5A / PVDF / Bi₂Te₃ material parameters | §2.1, Table 1 |
| table2_simulation_matrix.csv | Parametric simulation matrix (8 parameters) | §3.2, Table 2 |
| fig6_table3_ml_performance.csv | ML model metrics (also serves as Table 3) | §4.4, Table 3 |

## Figures
| File | Content | Paper Section |
|------|---------|---------------|
| fig3_peh_freq_power.csv | Piezoelectric frequency–power curves (4 beam lengths) | §4.1, Fig. 3 |
| fig3_meta.json | Resonance frequencies and peak powers metadata | §4.1 |
| fig4_teg_deltaT_output.csv | TEG ΔT vs voltage/power (3 N values, ±Thomson) | §4.2, Fig. 4 |
| fig5_hybrid_comparison.csv | Hybrid vs PEH vs TEG power comparison (5 conditions) | §4.3, Fig. 5 |
| fig7_ml_scatter.csv | ML predicted vs simulated temperature (4 models) | §4.4, Fig. 7 |
| fig8_3d_surface.csv | 3D surface: beam length × ΔT → total power | §4.5, Fig. 8 |
| fig9_pareto_front.csv | Pareto optimal front: power vs sensing MAE | §4.5, Fig. 9 |
| fig10_radar_chart.csv | Radar chart: 5 design schemes × 6 criteria | §4.6, Fig. 10 |

## Datasets
| File | Content |
|------|---------|
| simulation_dataset_full.csv | Full parametric sweep dataset (576+ cases) for ML training |

## Validation
| File | Content |
|------|---------|
| validation_resonance_freq.csv | Full composite beam model vs Rayleigh quotient |
| validation_teg_voltage.csv | T-dependent Seebeck+Thomson vs constant-property linear |
| validation_peh_power.csv | Q-dependent distributed model vs fixed-Q lumped SDOF |
| validation_experimental_peh.csv | PEH model vs Erturk & Inman experimental data |
| validation_experimental_teg.csv | TEG model vs published Bi₂Te₃ module data |

## Notes
- PEH: Euler-Bernoulli composite beam + tip mass + electromechanical stiffening
- TEG: Temperature-dependent Seebeck, ZT degradation, Thomson correction
- Hybrid: ratio-dependent coupling loss, physical output floor constraint
- Validation: analytical baselines and published experimental comparisons

---

*Funded by NSFC (51476148), Henan Innovation Team (CXTD2011042), Henan ST Project (252102241021).*
