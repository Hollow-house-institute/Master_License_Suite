# License Binding Schema — HHI Materials

All Hollow House Institute datasets and artifacts MUST include explicit license binding metadata.

## Required Fields

Every dataset or artifact SHALL declare:

- `license_id`
- `license_version`
- `issuing_authority`
- `training_permitted` (boolean)
- `derivatives_permitted` (boolean)
- `commercial_use_permitted` (boolean)
- `attribution_required` (boolean)
- `governing_standard` (HHI-LIC-01)
- `hash_reference` (optional)

## Example (YAML)

```yaml
license_id: RAP-DL-1.0
license_version: 1.0
issuing_authority: Hollow House Institute
training_permitted: false
derivatives_permitted: false
commercial_use_permitted: false
attribution_required: true
governing_standard: HHI-LIC-01

---

## Governance & Terminology Binding
Terminology inherits definitions from:  
AI Governance Glossary v1.3.0 — Hollow House Institute  
https://github.com/hhidatasettechs-oss/Hollow_House_Standards_Library  

Terms must not be reinterpreted, substituted, or redefined.

## Decision Boundary
Human-in-the-loop authority remains the final decision boundary.

## Execution-Time Governance
This license enforces constraints at execution time and does not define governance.


---

## Governance & Terminology Binding
Terminology inherits definitions from:  
AI Governance Glossary v1.3.0 — Hollow House Institute  
https://github.com/hhidatasettechs-oss/Hollow_House_Standards_Library  

Terms must not be reinterpreted, substituted, or redefined.

## Decision Boundary
Human-in-the-loop authority remains the final decision boundary.

## Execution-Time Governance
This license enforces constraints at execution time and does not define governance.

