# Project-level metadata descriptor

This file explains the fields in `project.yaml`.  
Project metadata captures the broad context of the entire research project.

## Field explanations

### `project_id`
Short alphanumeric ID, unique within the lab.

### `title`
Full name of the project.

### `short_title`
Shorthand nickname used internally.

### `principal_investigator`
Required object with name, affiliation, and email.

### `contributors`
List of people involved, with roles such as:
- conceptualization
- investigation
- data curation
- software
- supervision
- writing

### `lab`
The lab or unit conducting the project.

### `funding`
Agencies, grants, or other funding sources.

### `project_description`
Short narrative summary.

### `keywords`
Free-text topical keywords.

### `license`
Recommended: `CC BY 4.0` for metadata and documentation.

### `repository_url`
Where code/data live.

### `data_access`
- `open`  
- `restricted`  
- `closed`  

Describe how access works in plain language.

### `ethics`
Ethics approval details, if applicable.

### `timeline`
Start/end dates and project status.

### `links`
Protocol, preregistration, OSF, website, etc.
