# Kalif Shear

### Life sciences, scientific Python and AI evaluation

I build tools that help scientists work with reliable data and defensible results. My background spans CAR-T and iPSC-derived cell therapies, flow cytometry, analytical development, QC/QA and scientific workflow automation. I also create and review scientific and software tasks for AI evaluation.

My work connects experimental judgment with reproducible analysis: define the question, preserve the evidence, test plausible alternatives and explain what the result supports.

[TrueGate Bio](https://truegatebio.com)

## Tasks

Programming tasks for scientific data analysis, written for AI evaluation. Each repository holds the task statement, practice data and a starter; the reference solution and verifier are kept private so the tasks stay usable for evaluation.

| Task | What to look for |
|---|---|
| [Potency Assay Qualification](https://github.com/hiddenlif/PotencyAssayQualification) | Qualify a cell-based reporter-gene potency assay from plate, dilution and liquid-handler records: relative potency against a reference, curve acceptance, accuracy, precision and a study verdict. Synthetic studies, three signed-off practice studies. |
| [Lab Data Recovery](https://github.com/hiddenlif/LabDataRecovery) | Repair a Python/SQLite application so corrected evidence, queued analyses, historical reports and recovery from incomplete migrations agree, while preserving immutable history. |

## Analysis projects

| Project | What to look for |
|---|---|
| [Gene Expression Models](https://github.com/hiddenlif/GeneExpressionModels) | A frozen prediction pipeline evaluated across independent public expression studies, with leakage controls and explicit interpretation limits. |
| [Cytometry Gating](https://github.com/hiddenlif/CytometryGating) | Public FCS provenance, reviewable event plots and openCyto/FlowKit engineering checks. Biological performance remains a separate validation question. |
| [RNA-seq Analysis](https://github.com/hiddenlif/RNASeqAnalysis) | Real public bulk RNA-seq data, donor-held-out classification and exact paired inference that respects the limits of a small donor sample, with a label-shuffle negative control that shows what feature-selection leakage looks like. |
| [Biology Problems](https://github.com/hiddenlif/BiologyProblems) | Six cases in assay mathematics and inference pitfalls: receptor binding, counting-bead uncertainty, rare-cell detection, absolute counts, technical replication and donor leakage, with independent calculations and boundary tests. |
| [Lab Data Reconciliation](https://github.com/hiddenlif/LabDataReconciliation) | Traceable resolution of duplicates, revisions, units and metadata conflicts without silently reusing obsolete results, checked row by row against an independent formulation of the policy. |

## How I approach quality

- Preserve source identity, units, sample relationships and analysis provenance.
- Keep preprocessing and model selection inside the appropriate validation boundary.
- Test malformed inputs, edge cases and biological constraints, not just expected outputs.
- Check important calculations against an independent formulation.
- Document uncertainty and distinguish computational checks from biological or clinical validation.

These repositories use public research data or explicitly synthetic examples. Their READMEs provide source attribution, reproducibility instructions and known limitations; the analysis projects also include executed findings. Project-specific AI assistance is disclosed where applicable.
