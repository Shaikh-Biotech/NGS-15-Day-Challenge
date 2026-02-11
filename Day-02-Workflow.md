# Day 2: NGS Workflow & Library Prep

## The Workflow Overview
1. **Wet Lab:** Sample Extraction -> Library Prep -> Sequencing.
2. **Dry Lab:** Primary (Base calling) -> Secondary (Alignment) -> Tertiary (Interpretation).

## Library Prep Steps
- **Fragmentation:** Breaking DNA into 200-600bp chunks.
- **End Repair/A-Tailing:** Preparing ends for adapters.
- **Ligation:** Adding P5/P7 adapters and barcodes (Indices).
- **PCR Enrichment:** Increasing library yield.

## Quality Control (QC)
- **Qubit:** Fluorometric quantification (more accurate than Nanodrop).
- **Bioanalyzer:** Visualizing fragment size distribution.
- **FastQC:** Assessing raw data quality (Phred scores).
