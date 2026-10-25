# RepairScopeX — Diffusion language model repair and evaluation

Research notebook archive for **When Repair Is Unnecessary: Decoding-Budget Confounds and Intervention Reliability in Diffusion Language Models**.

**Authors:** Badampudi Agasthya Anirudh; Subramaniyaswamy V (corresponding author).

## Repository layout

- `notebooks/01_foundations/`: task generators, AR controls, early Dream/SDLM experiments.
- `notebooks/02_native_repair/`: Dream, ALoDLM, MDLM, BD3LM source and native repair studies.
- `notebooks/03_evaluability/`: NB29 and E01–E05 evidence on scorable answers and decoding length.
- `notebooks/04_policy_and_mechanism/`: E06–E12, calibration, mechanism studies and V2 protocols.
- `notebooks/05_external_validation/`: R02–R08 external testing and grading.
- `notebooks/legacy_versions/`: historical revisions and previous notebook variants.
- `NOTEBOOK_INVENTORY.csv`: recovered source and execution/provenance status.
- `results/`: result archive manifest; binary model/data archives are *not* indiscriminately mirrored.
- `MISSING_OR_UNVERIFIED.md`: sources and experiments that remain unavailable or unverified.

Notebooks are preserved as **source code**, but outputs may be stripped before publication to avoid leaking credentials, personally identifiable notes or private model records. A notebook being present **does not** establish that its experiments were executed.

## Empirical scope and negative results

The archived 774 native-repair attempts comprise nonexchangeable cohorts and should not be pooled into a single success rate. On 36 prospective E10 problems, the frozen router returned 20 correct compared with 24 under preservation; it repaired one initially unsuccessful response while damaging five initially correct responses. In R06, 256-token initial generation achieved 28/48 strict successes versus 4/48 at 128 tokens. A separate fixed R08 cohort produced 19/48 versus 0/48; 256-token regeneration also achieved 19/48. None of these results validates a universally superior repair policy.

## Reproduction

Open the target notebook in Google Colab, inspect its first cells for runtime and dependency constraints, acquire any third-party weights or datasets under their original terms, and check the expected protocol/manifest before comparing outputs. CUDA availability is not guaranteed on free Colab; some runs require model licensing or an authorized Hugging Face session. Keep credentials in private runtime secrets, never in notebooks or GitHub.

Use `NOTEBOOK_INVENTORY.csv` and `MISSING_OR_UNVERIFIED.md` to distinguish notebooks from result-only checkpoints and planned but incomplete protocols.

## Publication status

This is an ongoing research archive. No journal acceptance, persistent dataset DOI, equivalence finding or comprehensive redistributability clearance is claimed. Consult the research manuscript and coauthor-approved disclosures before citing results. Third-party datasets and checkpoints retain their original licenses.
