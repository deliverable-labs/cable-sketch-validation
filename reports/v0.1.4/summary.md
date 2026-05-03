# Validation Report — v0.1.4 (2026-05-03)

Engine: `0.2.0` · method: `neher-mcgrath-1957` · catalog: `cigre-tb880`

## Summary

| Total | Active | Passing | Expected fail | Skipped | Failing |
| ----- | ------ | ------- | ------------- | ------- | ------- |
| 48 | 35 | 35 | 0 | 13 | 0 |

## Cases

| Case | Source | Status | Checks | Worst deviation | Report |
| ---- | ------ | ------ | ------ | --------------- | ------ |
| cigre-tb880-0-1-buried-trefoil | cigre-tb880 | ✅ pass | 5/5 | +0.397% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/cigre-tb880-0-1-buried-trefoil.pdf) |
| cigre-tb880-0-2-hdpe-trefoil | cigre-tb880 | ✅ pass | 6/6 | -0.727% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/cigre-tb880-0-2-hdpe-trefoil.pdf) |
| cigre-tb880-0-3-pvc-concrete-flat | cigre-tb880 | ✅ pass | 8/8 | +4.989% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/cigre-tb880-0-3-pvc-concrete-flat.pdf) |
| cigre-tb880-3-hpff-thermal-backfill | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-0-4-free-air-solar | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-0-5-unfilled-trough | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-1-flat-buried | cigre-tb880 | ✅ pass | 14/14 | -0.050% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/cigre-tb880-case-1-flat-buried.pdf) |
| cigre-tb880-case-1-trefoil-buried | cigre-tb880 | ✅ pass | 7/7 | +0.074% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/cigre-tb880-case-1-trefoil-buried.pdf) |
| cigre-tb880-case-2-30kv-submarine | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-4-33kv-land | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-5-400kv-lpof-flat | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-5-400kv-lpof-trefoil | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-6-400kv-submarine-ac | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-7-320kv-hvdc-submarine | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-case-8-220kv-3c-submarine-export | cigre-tb880 | ⏭ skip | — | — | — |
| cigre-tb880-p154-cross-bond-m-su | cigre-tb880 | ✅ pass | 1/1 | — | — |
| cigre-tb880-p154-cross-bond-m-su-2-1 | cigre-tb880 | ✅ pass | 1/1 | — | — |
| cigre-tb880-p154-cross-bond-m-su-balanced | cigre-tb880 | ✅ pass | 1/1 | — | — |
| cigre-tb880-p155-flat-foil-eddy | cigre-tb880 | ✅ pass | 3/3 | — | — |
| cigre-tb880-p93-flat-lambda-prime | cigre-tb880 | ✅ pass | 3/3 | — | — |
| diagnostic-equal-share-missing-demand | invariant | ✅ pass | 0/0 | — | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/diagnostic-equal-share-missing-demand.pdf) |
| diagnostic-temp-at-load-missing-current | invariant | ✅ pass | 0/0 | — | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/diagnostic-temp-at-load-missing-current.pdf) |
| invariant-deeper-burial-lower-ampacity | invariant | ⏭ skip | — | — | — |
| invariant-doubling-rho-doubles-t4 | invariant | ⏭ skip | — | — | — |
| invariant-loss-factor-from-load | invariant | ✅ pass | 1/1 | +0.000% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/invariant-loss-factor-from-load.pdf) |
| invariant-symmetry-2x2 | invariant | ⏭ skip | — | — | — |
| invariant-zero-load-zero-temp-rise | invariant | ✅ pass | 3/3 | +0.000% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/invariant-zero-load-zero-temp-rise.pdf) |
| nec-annexB-2-5-3duct-1000kcmil-al-rho90-lf100 | nec-table | ✅ pass | 1/1 | -0.253% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-3duct-1000kcmil-al-rho90-lf100.pdf) |
| nec-annexB-2-5-3duct-250kcmil-cu-rho60-lf50 | nec-table | ✅ pass | 1/1 | -3.122% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-3duct-250kcmil-cu-rho60-lf50.pdf) |
| nec-annexB-2-5-3duct-500kcmil-cu-rho90-lf100 | nec-table | ✅ pass | 1/1 | -1.311% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-3duct-500kcmil-cu-rho90-lf100.pdf) |
| nec-annexB-2-5-6duct-1000kcmil-al-rho120-lf100 | nec-table | ✅ pass | 1/1 | +0.861% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-6duct-1000kcmil-al-rho120-lf100.pdf) |
| nec-annexB-2-5-6duct-500kcmil-cu-rho120-lf100 | nec-table | ✅ pass | 1/1 | +0.050% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-6duct-500kcmil-cu-rho120-lf100.pdf) |
| nec-annexB-2-5-6duct-500kcmil-cu-rho90-lf100 | nec-table | ✅ pass | 1/1 | +0.278% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-6duct-500kcmil-cu-rho90-lf100.pdf) |
| nec-annexB-2-5-9duct-1000kcmil-al-rho120-lf100 | nec-table | ✅ pass | 1/1 | +2.857% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-9duct-1000kcmil-al-rho120-lf100.pdf) |
| nec-annexB-2-5-9duct-1000kcmil-al-rho90-lf100 | nec-table | ✅ pass | 1/1 | +3.148% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-9duct-1000kcmil-al-rho90-lf100.pdf) |
| nec-annexB-2-5-9duct-500kcmil-cu-rho120-lf100 | nec-table | ✅ pass | 1/1 | +0.639% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-9duct-500kcmil-cu-rho120-lf100.pdf) |
| nec-annexB-2-5-9duct-500kcmil-cu-rho60-lf50 | nec-table | ✅ pass | 1/1 | +0.881% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-9duct-500kcmil-cu-rho60-lf50.pdf) |
| nec-annexB-2-5-9duct-500kcmil-cu-rho90-lf100 | nec-table | ✅ pass | 1/1 | +1.059% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-5-9duct-500kcmil-cu-rho90-lf100.pdf) |
| nec-annexB-2-6-1duct-3c-4-0awg-cu-rho60-lf50 | nec-table | ✅ pass | 1/1 | -3.284% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-6-1duct-3c-4-0awg-cu-rho60-lf50.pdf) |
| nec-annexB-2-6-1duct-3c-500kcmil-cu-rho90-lf100 | nec-table | ✅ pass | 1/1 | -4.422% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-6-1duct-3c-500kcmil-cu-rho90-lf100.pdf) |
| nec-annexB-2-6-3duct-3c-4-0awg-al-rho60-lf50 | nec-table | ✅ pass | 1/1 | -2.677% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-6-3duct-3c-4-0awg-al-rho60-lf50.pdf) |
| nec-annexB-2-6-3duct-3c-500kcmil-al-rho90-lf100 | nec-table | ✅ pass | 1/1 | -2.520% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-6-3duct-3c-500kcmil-al-rho90-lf100.pdf) |
| nec-annexB-2-6-3duct-3c-500kcmil-cu-rho90-lf100 | nec-table | ✅ pass | 1/1 | -2.281% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-6-3duct-3c-500kcmil-cu-rho90-lf100.pdf) |
| nec-annexB-2-6-6duct-3c-500kcmil-cu-rho120-lf100 | nec-table | ✅ pass | 1/1 | -0.333% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nec-annexB-2-6-6duct-3c-500kcmil-cu-rho120-lf100.pdf) |
| nm-1957-app-example-1 | nm-paper | ✅ pass | 12/12 | +26.856% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nm-1957-app-example-1.pdf) |
| nm-1957-app-example-2 | nm-paper | ✅ pass | 3/3 | +4.066% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/nm-1957-app-example-2.pdf) |
| nm-1957-table-II-skin-prox | nm-paper | ✅ pass | 18/18 | — | — |
| temperature-at-equal-share-load | invariant | ✅ pass | 6/6 | +0.000% | [PDF](https://github.com/deliverable-labs/cable-sketch-validation/releases/download/v0.1.4/temperature-at-equal-share-load.pdf) |

[Machine-readable report.json →](report.json)