# Circos Genomic Visualization Repository

This repository contains Circos configuration files, data, and visualizations for genomic analysis projects, supporting research publications in computational biology and genomics.

## Overview

[Circos](http://circos.ca/) is a powerful software package for visualizing data and information in a circular layout, particularly well-suited for genomic data visualization. This repository demonstrates various applications of Circos for:

- **Chromosomal data visualization** with ideograms and karyotypes
- **Comparative genomics** analysis
- **Gene expression** profiling and differential analysis
- **miRNA** target analysis and regulatory networks
- **Principal Component Analysis (PCA)** visualization
- **Trisomy** and chromosomal aberration studies

## Repository Structure

### Core Visualization Projects

- **`1_stackedHistograms/`** - Basic stacked histogram visualizations showing multi-dimensional genomic data across chromosomes
- **`2_labelPractice/`** - Examples of labeling and annotation techniques for genomic features
- **`3_complexHistograms/`** - Advanced histogram configurations with multiple data tracks and expression datasets
- **`4_PCA_LMD_contextual/`** - Principal Component Analysis visualizations with contextual genomic information
- **`5_TrisomyContextual/`** - Chromosomal aberration analysis focusing on trisomy conditions

### Specialized Analysis

- **`miRNA/`** - Comprehensive microRNA analysis pipeline including:
  - miRNA target prediction and validation
  - Differential expression analysis
  - PCA-based clustering of miRNA profiles
  - Database cross-referencing for functional annotation

### Publications

- **`z_Publication_Thesis/`** - Contains research publications and thesis documents that utilize the visualizations generated from this repository

## Key Features

### Visualization Capabilities
- **Multi-track data display** with customizable radial positioning
- **Color-coded expression levels** and statistical significance
- **Interactive legends** and annotation systems
- **High-resolution output** in PNG and SVG formats
- **Configurable ideograms** for human and other model organisms

### Data Integration
- Support for various genomic data formats
- Integration with expression databases
- Compatibility with standard bioinformatics file formats
- Automated data preprocessing pipelines

## Getting Started

### Prerequisites
- [Circos](http://circos.ca/) software package
- Perl environment with required modules
- Standard bioinformatics data formats (BED, GFF, etc.)

### Basic Usage

1. **Navigate to a project directory:**
   ```bash
   cd 1_stackedHistograms/
   ```

2. **Run Circos with the configuration:**
   ```bash
   circos -conf circos.conf
   ```

3. **Output files will be generated:**
   - `circos.png` - High-resolution raster image
   - `circos.svg` - Scalable vector graphics

### Configuration Files

Each project directory contains:
- **`circos.conf`** - Main configuration file
- **`ideogram.conf`** - Chromosome ideogram settings
- **`ticks.conf`** - Tick marks and scale configuration
- **Data files** - Input data in Circos-compatible formats

## Data Sources

The visualizations in this repository utilize:
- **Human genome reference** (GRCh37/hg19 and GRCh38/hg38)
- **Gene expression databases** (GEO, TCGA, etc.)
- **miRNA databases** (miRBase, TargetScan)
- **Pathway databases** (KEGG, GO, Reactome)

## Applications

This repository supports research in:
- **Cancer genomics** and tumor profiling
- **Developmental biology** and gene regulation
- **Comparative genomics** across species
- **Pharmacogenomics** and drug response
- **Population genetics** and evolutionary studies

## Contributing

When adding new visualizations:
1. Create a descriptive directory name
2. Include all necessary configuration files
3. Provide sample data or data generation scripts
4. Document any special requirements or dependencies
5. Update this README with project descriptions

## Citation

If you use visualizations or methods from this repository, please cite the relevant publications found in the `z_Publication_Thesis/` directory.

## License

This repository is provided for academic and research purposes. Please refer to individual data sources for their respective licensing terms.

## Contact

For questions about specific visualizations or methodologies, please refer to the corresponding publication or create an issue in this repository.

---

*Generated with Circos v0.69+ • Human Genome Assembly GRCh38*