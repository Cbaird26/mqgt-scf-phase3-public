# MQGT-SCF Phase 3 — public working set

Scripts, outputs and notes from Phase 3 of the MQGT-SCF research program
(C.M. Baird and ZoraASI, 2026), released as the working record behind the
corrected unified edition of 11 September 2026. `manifest.json` carries the
SHA-256 hashes that pin each script and document to that edition.

**Status:** theoretical and software-validation work. Nothing here reports an
experimental detection; EMP-01 is preregistered and not yet run.

## Contents

| Area | Files |
| --- | --- |
| Part 0 problems | `radiative_sequestering.py` (+ `.csv`), `coarse_graining_bridge.py` (+ synthetic `.csv`), `exclusion_scan.py` with `exclusion_contours.csv` / `exclusion_profile_1d.csv` |
| M-2 gate (reservoir model, η) | `bridge_c_full_eta_extended.py` (+ `.csv`), `bridge_c_gamma_norm.py` |
| Phase 3 UV completion (asymptotic-safety fixed-point search) | `bridge_d_uv.py`, `bridge_d_uv_4scalar.py` (+ `_output.json`), write-up `UV_COMPLETION_SUBMISSION.md` |
| Neutrino portal | `neutrino_portal.py` (+ `_output.json`), write-up `NEUTRINO_PORTAL_SUBMISSION.md` |
| TUFT track | `tuft_alpha_identity.py` (T-1), `tuft_gminus2_closed.py` (T-3), `tuft_s7_spectral.py`, `compactification_map.py`, `LITERATURE_SEARCH_T1_T3.md` |
| EMP-01 preregistered protocol | `emp01_protocol.md`, `emp01_analyzer.py` (fail-closed analyzer), `generate_emp01_synthetic.py`, `emp01_synthetic.csv` |
| Corrected edition record | `ZOHAR_CORRECTED_2026-09-11/` (errata and corrected methods note, LaTeX + audit report), `manifest.json` |
| Zenodo metadata | `zenodo_fix.py`, `zenodo_metadata_fix_payload_21910349_CORRECTED.json` |

All scripts are standalone Python 3 (NumPy/SciPy where imported) and write
their outputs next to themselves.

## Related repositories

- [mqgt-scf-continued](https://github.com/Cbaird26/mqgt-scf-continued) — forward development line and research ledger
- [mqgt-scf-independent-verification](https://github.com/Cbaird26/mqgt-scf-independent-verification) — frozen verification record
- [toe-empirical-validation](https://github.com/Cbaird26/toe-empirical-validation) — replication-ladder spine

## License

Text, notes and data: CC BY 4.0 (see `LICENSE`). Cite the Zenodo record of the
corrected edition where one is given in `manifest.json`.
