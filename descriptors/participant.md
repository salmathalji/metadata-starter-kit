# Participant-level metadata descriptor

Explains the entries in `participant.yaml`.

Participants are represented as a list of objects.

---

## Field explanations (with coding schemes)

### `participant_id`
Local ID matching dataset files.

### `study_id`
Links back to study metadata.

---

### `sex`  
**Allowed values:**
- `female`  
- `male`  
- `intersex`  
- `prefer_not_to_say`  
- `unknown`  

These are intentionally broad to support inclusivity and privacy.  
Use whichever values apply, or extend locally if needed.

---

### `age_years`
Integer or decimal, age at time of participation.

---

### `handedness`  
**Allowed values:**
- `right`  
- `left`  
- `ambidextrous`  
- `unknown`  

---

### `country_of_residence`
Two-letter ISO codes recommended (e.g. `DE`, `UK`, `US`).

### `vision_status`
Short description (e.g., `normal`, `corrected-to-normal`).

### `inclusion_status`  
Common values:
- `included`  
- `excluded`  
- `screen_fail`  
- `withdrawn`  

### `exclusion_reason`
Non-identifying short text.

### `group_assignment`
Experimental group label.

### `notes`
Free-text, non-identifying details.
