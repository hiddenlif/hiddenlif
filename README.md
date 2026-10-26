# Kalif Shear

### Cell therapy, scientific Python and AI evaluation

I build tools that help scientists work with reliable data and defensible results. My background spans CAR-T and iPSC-derived cell therapies, flow cytometry, analytical development, QC/QA and scientific workflow automation. I also create and review scientific and software tasks for AI evaluation.

My work connects experimental judgment with reproducible analysis: define the question, preserve the evidence, test plausible alternatives and explain what the result supports.

[TrueGate Bio](https://truegatebio.com)

## Start here

| Featured project | What it demonstrates | Status and data |
|---|---|---|
| [Gene Expression Models](https://github.com/hiddenlif/GeneExpressionModels) | Freeze ER-status prediction pipelines in one study, then evaluate discrimination, probabilities and decisions in another. | Completed retrospective analysis; two public cohorts. |
| [RNA-seq Analysis](https://github.com/hiddenlif/RNASeqAnalysis) | Hold out donors, respect the unit of inference and demonstrate feature-selection leakage with a negative control. | Completed secondary analysis; public bulk RNA-seq data. |
| [Cytometry Gating](https://github.com/hiddenlif/CytometryGating) | Preserve public FCS provenance, inspect event plots and check gate transfer between openCyto and FlowKit. | Development project with executed engineering checks; biological gating performance unvalidated. |
| [Lab Data Reconciliation](https://github.com/hiddenlif/LabDataReconciliation) | Resolve revisions, duplicates, units and conflicting metadata with a traceable policy and an independent differential implementation. | Completed analysis and reusable CLI; synthetic exports. |
| [Potency Assay Qualification](https://github.com/hiddenlif/PotencyAssayQualification) | An AI coding task covering curve acceptance, relative potency, accuracy, precision and a study verdict. | Public task starter and three synthetic practice studies; reference and verifier private. |
| [Virtual Lab: flow cytometry](https://github.com/hiddenlif/VirtualLabFlowCytometry) | An AI task combining acquisition choices, controls, spillover unmixing, gates and rare-population uncertainty. | Interactive synthetic simulator; local reference and starter checks. |

## Virtual labs

Each virtual lab is a runnable simulator: choose a measurement, control or intervention, receive newly simulated evidence, and decide what it supports. Observations are synthetic unless a lab cites public source data.

### Interactive research labs

| Lab | What you do | Data and status |
|---|---|---|
| [Virtual Lab: iPSC bioreactor](https://github.com/hiddenlif/VirtualLabIPSCBioreactor) | Run an iPSC expansion-and-banking campaign in a local web app: request measurements, adjust perfusion, investigate instrument faults and make a simulated QC recommendation. | Synthetic, documented process model; not calibrated to experimental campaigns. Executed comparator study and tests included. |
| [Virtual Lab: spatial tumor atlas](https://github.com/hiddenlif/VirtualLabSpatialTumor) | Explore a measured 2D colorectal cancer atlas: quantify CD8-to-tumor proximity, reconstruct a masked protein channel and run conditional movement scenarios. | Public CODEX data (CC BY 4.0); movement is simulated and makes no clinical predictions. Executed investigation and tests included. |

### AI evaluation labs

These repositories publish the task statement, simulator, practice material and starter. Reference solutions, held-out cases and verifiers remain private.

| Lab | Required work | Lab type |
|---|---|---|
| [Virtual Lab: flow cytometry](https://github.com/hiddenlif/VirtualLabFlowCytometry) | Allocate controls and events, unmix signals, define gates and estimate rare-cell frequencies with intervals. | Interactive synthetic lab. |
| [Virtual Lab: vector copy number](https://github.com/hiddenlif/VirtualLabVectorCopyNumber) | Allocate digital PCR wells, DNA, controls and culture time across synthetic lots with inhibition and carryover. | Interactive synthetic lab. |
| [Virtual Lab: single-cell study design](https://github.com/hiddenlif/VirtualLabSingleCellDesign) | Budget donors, batches, cells and reads, then perform donor-aware treatment-effect analysis. | Interactive, simplified 40-gene count simulator. |
| [Virtual Lab: thermodynamic design](https://github.com/hiddenlif/VirtualLabThermodynamicDesign) | Choose calorimetry measurements and certify protein-lot responses while consuming stock. | Interactive synthetic lab. |
| [Virtual Lab: photochemical control](https://github.com/hiddenlif/VirtualLabPhotochemicalControl) | Interpret diagnostic readings and control a photoredox reactor under shared resource limits. | Interactive synthetic lab. |
| [Virtual Lab: clamp protocol](https://github.com/hiddenlif/VirtualLabClampProtocol) | Optimize an ordered voltage-clamp protocol across four disclosed synthetic ion-channel variants. | Prospective computational design. |

The evaluation-lab READMEs document local grader checks with a reference solution and an unchanged starter. Those checks establish bounded execution evidence. Measuring AI performance requires actual solver runs and a defined evaluation protocol. Simulation results also require separate empirical work before they support laboratory or clinical claims.

## Scientific AI evaluation tasks

These repositories publish the task statement, practice material and starter. Reference solutions, held-out cases and verifiers remain private. An unfinished starter is the intended input to an evaluation; it is labelled separately from a completed analysis.

| Task | Required work | Task type |
|---|---|---|
| [Reporter-Gene Potency Assay Qualification](https://github.com/hiddenlif/PotencyAssayQualification) | Qualify a potency assay using synthetic plate, dilution and liquid-handler records. Practice QA sign-offs are fictional scenario records. | Scientific coding task. |
| [Laboratory Data Recovery](https://github.com/hiddenlif/LabDataRecovery) | Repair a Python/SQLite application while preserving corrected evidence, queued analyses, historical reports and migration recovery. | Scientific software repair task; synthetic fixtures. |
| [ITC Binding Kinetics](https://github.com/hiddenlif/ITCBindingKinetics) | Infer binding and kinetic parameters from supplied synthetic calorimetry exports. | Fixed-data scientific analysis task. |

## Additional executed analysis cases

[Biology Problems](https://github.com/hiddenlif/BiologyProblems) contains six synthetic cell-therapy cases covering receptor binding, counting-bead uncertainty, rare-cell detection, absolute counts, technical replication and donor leakage. Executable notebooks, independent calculations, boundary checks and retained findings make the reasoning inspectable.

## How I approach quality

- Preserve source identity, units, sample relationships and analysis provenance.
- Keep preprocessing and model selection inside the appropriate validation boundary.
- Test malformed inputs, edge cases and biological constraints.
- Check important calculations against an independent formulation.
- Document uncertainty and distinguish computational checks from biological or clinical validation.

The repositories use public research data or explicitly synthetic examples. Each README describes reproducibility, attribution, execution status and limitations. Project-specific AI assistance is disclosed where applicable.
