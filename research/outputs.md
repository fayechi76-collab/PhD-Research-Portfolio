# Outputs and Reproducibility Status

[Home](../README.md) · [Overview](overview.md) · [Methods](methods.md) · [Evidence and Limitations](evidence.md)

## What exists now

| Output | Status | Public here? |
| --- | --- | --- |
| Literature corpus | 104,212 unique DOI records (31 Oct 2006 – 31 Oct 2026), DOI-normalised, stable IDs; 120 journal titles incl. 2,033 Lancet-family and 9,393 records from 10 further journals | Summary counts and de-identified classification fields for interactive filtering |
| Mechanism classification | 19 domains, 29 fine-grained entities, 38 study-design labels; 46,654 records linked to ≥1 entity | Category-level counts |
| Mechanism co-occurrence network | 1,084 mechanism pairs; edge = papers mentioning both mechanisms (co-occurrence, not causation) | Interactive aggregated map |
| Interactive Mechanism Evidence Atlas | Density network and mechanism × method heatmap with live filters | Public build in `atlas/` (category labels only; no titles, DOIs or abstracts) |
| Quality control | 14 data-integrity checks passed; source hash recorded | Summary |
| AI-assisted abstract review | 12 claims from 7 papers reviewed against abstracts. Human review and full-text verification remain pending. | Summary |
| Literature catalog explorer | Matrix, coverage and journal-source views of the catalog | Public build in `catalog/` (no titles, DOIs or PMIDs) |
| Exploratory Literature Map | Explore records by mechanism and study method | Public build in `pilot/` (labels only) |
| Literature census | Search-hit funnel and per-disorder counts | Public build in `census/` (aggregate counts) |

## In progress / planned

| Item | Next step |
| --- | --- |
| Search strings and retrieval log | Document source databases and dates for release |
| Label validation | Manually audit a random sample; report agreement rate |
| Full-text verification | Extend from abstract-level checks to full texts |
| Peer-reviewed publication | Manuscript planned; none to date |

The public site includes summary counts and de-identified record-level classification fields for filtering. The public catalog data omit article titles and DOI identifiers.

[← Evidence](evidence.md) · [Home](../README.md)
