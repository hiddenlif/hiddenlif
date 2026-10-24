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

## Virtual labs and scientific analysis tasks

These tasks include interactive simulated experimentation, computational experimental design and analysis of supplied synthetic data. Reference solutions, held-out cases and verifiers remain private. Historical reference checks establish only the stated local execution results.

| Task | Workflow and execution evidence |
|---|---|
| [Virtual Lab: thermodynamic design](https://github.com/hiddenlif/VirtualLabThermodynamicDesign) | Choose calorimetry experiments and use their simulated measurements to certify the operating response of two synthetic protein lots. Experiment choices affect both the observations and irreversible stock consumption. Three historical reference runs passed, each accepting all three campaigns. A no-op scored zero. These are local reference results, not blind solver results or platform approval. |
| [Virtual Lab: photochemical control](https://github.com/hiddenlif/VirtualLabPhotochemicalControl) | Choose diagnostic pulses for a simulated photoredox reactor, inspect their returned readings, and control flow, illumination, quenching, mitigation and product collection under shared resource limits. Successful execution of this exact version was not established in the reviewed execution records. An older version has successful reference receipts; those results do not validate this version. |
| [Virtual Lab: clamp protocol](https://github.com/hiddenlif/VirtualLabClampProtocol) | Design an ordered voltage-clamp protocol for a synthetic ion-channel model. Candidate protocols produce simulated currents and information metrics across four disclosed cell variants. This is prospective protocol optimization rather than a closed-loop acquisition campaign. A historical clean-extraction container run passed all five reference checks. A no-op and two legal negative controls scored zero. These are local reference results, not blind solver results or platform approval. |
| [Scientific Analysis: ITC binding kinetics](https://github.com/hiddenlif/ITCBindingKinetics) | Estimate binding affinity, enthalpy, stoichiometry and association rates from supplied synthetic calorimetry exports. This task analyzes fixed traces; it does not provide interactive experimental acquisition. Successful execution of this exact version was not established in the reviewed execution records. |

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
