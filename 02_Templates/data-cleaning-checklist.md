# Data Cleaning Checklist (template)

Use this before analysis and before making final figures/tables.

## 1) File integrity
- [ ] I saved a **raw** copy (read-only) and I work on a **clean** copy
- [ ] Variable names are clear (no duplicates)
- [ ] Units are consistent (e.g., mg/dL vs mmol/L)

## 2) Structure
- [ ] One row = one subject/animal/sample (or clearly defined long format)
- [ ] IDs are unique and stable (no re-used IDs)
- [ ] Group labels match protocol (control/stress/probiotic/etc.)

## 3) Missingness & outliers
- [ ] Missing values encoded consistently (NA; not 0)
- [ ] Missingness pattern checked (random vs systematic)
- [ ] Outliers flagged with criteria (predefined) and documented

## 4) QC & reproducibility
- [ ] Cleaning steps documented (what, why, when)
- [ ] Any exclusions have reasons (and counts)
- [ ] Final dataset version saved with date: `dataset_clean_YYYY-MM-DD.xlsx`

