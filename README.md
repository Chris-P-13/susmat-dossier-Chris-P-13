# Sus-Mat RDM Practice Dossier

**Program:** Sustainable Materials through Systems-Informed Thinking (Sus-Mat NRT)

## About This Repository

Practice project for the Sus-Mat RDM micro-credential. Contains a synthetic PP/CaSO4 cold-sintering dataset with three deliberate problems (disconnected identifiers, a mixed-unit column, and missing values) for hands-on data management exercises.

## Repository Contents

- `raw/` - original synthetic data files and notes (commit them, do not edit them)
- `processed/` - cleaned, validated data (empty until you add some)
- `analysis/` - scripts and notebooks (empty until you add some)
- `schema.yaml` - starter data dictionary, completed in Lesson 4
- `lab_notebook.md` - structured lab notebook
- `ids.csv` - ID crosswalk, filled in during Lesson 4
- `optional-enrichment/` - not used in the five-lesson course
- `.vscode/` - VS Code snippets for notebook entries
- `.gitignore` - keeps secrets out of Git; allows the synthetic raw data

You will create a data dictionary (in any format: YAML, CSV, or Markdown) in Lesson 4.

## Data Source

Skeleton training data based on cold-sintered PP/CaSO4 polymer-ceramic composites. Everything in `raw/` is SUS-MAT NRT training data, not real research data.

- `raw/PC-tensile-raw.csv` - tensile testing per ASTM D638 (Instron 5943, 100 N load cell, crosshead 0.5 mm/min)
- `raw/PC-synthesis-log.csv` - cold sintering synthesis conditions by batch (protocol PP-CaSO4 Cold Sinter v2.1)
- `raw/CT-metadata.csv` - X-ray micro-CT scan sessions (GE v|tome|x L300). `scan_id` is assigned by scan order, not by specimen batch.
- `raw/CT-scan-sheet.csv` - transcription of the handwritten CT scan sheet, tube labels as written

Reference: Lai et al., "Upcycling plastic waste into fully recyclable composites through cold sintering," *Materials Horizons*, 2024, 11, 2718–2728. DOI: 10.1039/D3MH01976D

---

## Identifiers

SID

PC-B01-S01, PC-B01-S02, PC-B01-S03, PC-B01-S04, PC-B01-S05, PC-B02-S01, PC-B02-S02, PC-B02-S03, PC-B02-S04, PC-B02-S05, PC-B03-S01, PC-B03-S02, PC-B03-S03, PC-B03-S04, PC-B03-S05,
PC-B03-S06, PC-B04-S01, PC-B04-S02, PC-B04-S03, PC-B04-S04, PC-B04-S05, PC-B05-S01, PC-B05-S02, PC-B05-S03, PC-B05-S04, PC-B05-S05, PC-B06-S01, PC-B06-S02, PC-B06-S03, PC-B06-S04, 
PC-B06-S05,

batch_id

B03-A, B03-B, B04-A, B04-B, B05-A, B05-B

scan_id

CT-001, CT-002, CT-003, CT-004, CT-005, CT-006, CT-007, CT-008, CT-009, CT-010, 
CT-011, CT-012, CT-013, CT-014, CT-015, CT-016, CT-017, CT-018, CT-019, CT-020, CT-021, CT-022, CT-023, CT-024, CT-025, CT-026, CT-027, CT-028, CT-029, CT-030, CT-031

*Crosswalk built in Lesson 4.

*This dossier was created as part of the [Sus-Mat NRT](https://susmat-nrt.web.app/) training program.*
