# Notebook completeness and provenance

Updated 25 October 2026. **54 recoverable original notebook source files** are present under `notebooks/` after deduplicating one misplaced copy. Cell output histories have been removed; the source cells remain. GitHub files are not evidence of execution.

## Known gaps

- **NB01 and NB04**: exact RepairScopeX notebook files not recovered from the accessible Library. Other projects' similarly numbered notebooks were deliberately excluded.
- **NB07**: an early region-repair/independence notebook was described in historical audits but its exact source was not recovered; NB08 is included.
- **NB17**: only historical audit evidence was available; the exact NB17 code was not recovered.
- **V2-15**: source code is present but the held-out run was blocked by the missing frozen calibration policy / failed advancement gate. Not an executed confirmatory success.
- Some notebooks are recovered only as their most recent corrected version, rather than every experimental revision.
- Older NB02–NB08 variants could be absent or incompletely recovered; the inventory is limited to files identified as belonging to RepairScopeX rather than matching bare notebook numbers from unrelated papers.

## Evidence versus source

The result snapshot ZIP files listed in `results/RESULT_ARCHIVE_MANIFEST.csv` were accessible in the research workspace but are **not mirrored** in the public repository. They can contain model-generated text, raw benchmark question content, blinded review forms and other materials requiring redistribution review. A ZIP of recorded results does not recreate the exact source notebook.

## Reproduction cautions

The archived cohorts are not exchangeable. Do not sum reused records or repeated model calls as independent tests. Maintain dataset/mode-specific license rules, checkpoint revisions and protocol hashes before reproducing.
