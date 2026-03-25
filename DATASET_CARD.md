---
language:
- en
license: mit
task_categories:
- tabular-classification
tags:
- economics
- credential-relaxation
- computational-economics
- labor-economics
- emerging-terminology
pretty_name: credential relaxation Economics Dataset
size_categories:
- n<1K
---

# credential relaxation Economics Dataset

## Dataset Description
### Summary
Synthetic 200-row dataset for `credential relaxation` measurement and computational experiments.

### Supported Tasks
- Economic analysis
- Labor Economics research
- Computational economics

### Languages
- English (metadata and documentation)
- Python (code examples)

## Dataset Structure
### Data Fields
- `id`: Unique observation id
- `quarter`: Synthetic quarter
- `labor_shortage`: Gap between open roles and qualified applicants
- `skills_based_hiring_share`: Share of openings without formal degree filters
- `degree_requirement_rate`: Share of jobs requiring degree credentials
- `certification_requirement_rate`: Share of jobs requiring formal certifications
- `hiring_time_days`: Time-to-fill metric in days
- `offer_acceptance_rate`: Accepted offers divided by offers made
- `retention_6m`: Six-month retention rate for new hires
- `credential_relaxation_index`: Composite term index

### Data Splits
- Full dataset: 200 examples

## Dataset Creation
### Source Data
Synthetic data generated for demonstrating credential relaxation applications.

### Data Generation
Channels are sampled from controlled distributions with correlated structure. The term index is computed from normalized channels and directional weights.

## Considerations
### Social Impact
Research-only synthetic data for method development and reproducibility testing.

## Additional Information
### Licensing
MIT License - free for academic and commercial use.

### Citation
@dataset{credential-relaxation2026,
title={{credential relaxation Economics Dataset}},
author={{Economic Research Collective}},
year={{2026}}
}
