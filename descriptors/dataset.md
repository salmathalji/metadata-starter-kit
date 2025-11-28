# Dataset-level metadata descriptor

Explains `dataset.yaml`.

Dataset-level metadata describes:
- where the data live  
- how they’re structured  
- what variables mean  
- how QC was handled  

---

## Field explanations

### `dataset_id`, `dataset_name`
Stable identifiers and human-readable names.

### `study_id`, `project_id`
Cross-links to other metadata files.

### `dataset_description`
Short overview of contents.

### `version`
Semantic versioning recommended (e.g., `1.0.0`).

### `release_date`
`YYYY-MM-DD`.

### `associated_publications`
List of DOIs and citations.

---

## File structure

Each file entry includes:
- `path`  
- `description`  
- `file_pattern`  
- `modality`  
- `device_id` (if applicable)

---

## Tabular variables

Each table entry defines:
- file pattern  
- key columns  
- list of variable descriptors  

### Variable descriptor fields:
- `name`
- `type` (`string`, `number`, `integer`, `boolean`, `datetime`)
- `description`
- `format` (optional)
- `required` (boolean)

---

## Notes
Use this for caveats or additional context.
