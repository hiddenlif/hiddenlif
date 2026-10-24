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

These tasks include interactive simulated experimentation, computational experimental design and analysis of supplied synthetic data. Reference solutions, held-out cases and verifiers remain private. Each task's stated results are local reference runs, not blind solver results.

| Task | Workflow and execution evidence |
|---|---|
| [Virtual Lab: flow cytometry](https://github.com/hiddenlif/VirtualLabFlowCytometry) | Choose controls, tubes and event counts on a simulated cytometer, then unmix spillover, set gates and estimate a rare population's frequency with an interval in four synthetic samples. In a local Docker run of the grader the reference was accepted on 8 of 8 held-out cases and the unchanged starter scored zero. Local results, not blind solver results. |
| [Virtual Lab: vector copy number](https://github.com/hiddenlif/VirtualLabVectorCopyNumber) | Allocate simulated digital PCR wells, DNA input, controls and culture time across three synthetic lots to estimate integrated copies per cell-equivalent despite inhibition, plate background and non-integrated carryover. In a local Docker run of the grader the reference was accepted on 8 of 8 held-out cases and the unchanged starter scored zero. Local results, not blind solver results. |
| [Virtual Lab: single-cell study design](https://github.com/hiddenlif/VirtualLabSingleCellDesign) | Spend a fixed budget on donors, batches, cells and sequencing depth, then estimate cell-type-specific treatment effects from the simulated count matrices with a donor-aware analysis and a cost ledger. In a local Docker run of the grader the reference was accepted on 8 of 8 held-out cases and the unchanged starter scored zero. Local results, not blind solver results. |
| [Virtual Lab: thermodynamic design](https://github.com/hiddenlif/VirtualLabThermodynamicDesign) | Choose calorimetry experiments and use their simulated measurements to certify the operating response of two synthetic protein lots. Experiment choices affect both the observations and irreversible stock consumption. In a local Docker run on 2026-10-24, reference accepted all three campaigns, reward 1 and the starter 0. Local results, not blind solver results. |
| [Virtual Lab: photochemical control](https://github.com/hiddenlif/VirtualLabPhotochemicalControl) | Choose diagnostic pulses for a simulated photoredox reactor, inspect their returned readings, and control flow, illumination, quenching, mitigation and product collection under shared resource limits. In a local Docker run on 2026-10-24, reference passed 20 of 20 sessions, reward 1 and the starter 0 of 20. Local results, not blind solver results. |
| [Virtual Lab: clamp protocol](https://github.com/hiddenlif/VirtualLabClampProtocol) | Design an ordered voltage-clamp protocol for a synthetic ion-channel model. Candidate protocols produce simulated currents and information metrics across four disclosed cell variants. This is prospective protocol optimization rather than a closed-loop acquisition campaign. In a local Docker run on 2026-10-24, reference passed 5 of 5 checks, reward 1 and the starter 0. Local results, not blind solver results. |
| [Scientific Analysis: ITC binding kinetics](https://github.com/hiddenlif/ITCBindingKinetics) | Estimate binding affinity, enthalpy, stoichiometry and association rates from supplied synthetic calorimetry exports. This task analyzes fixed traces; it does not provide interactive experimental acquisition. In a local Docker run on 2026-10-24, reference 8 of 8 sealed experiments, reward 1 and the starter 0 of 8. Local results, not blind solver results. |

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
