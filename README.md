# Transcription Factor ChIP-seq Heatmap Browser

A web-based visualization tool for exploring transcription factor binding patterns using Hi-ChIP.

## Features

- **Multi-TF Support**: KLF4, NANOG, OCT4, RAD21
- **ENCODE Integration**: 19 ChIP-seq experiments from ENCODE consortium
- **Genome Coverage**: Complete autosomal chromosomes (chr1-chr22)
- **High Resolution**: 2MB genomic windows
- **Cloud Storage**: Hybrid GitHub Pages + Aliyun OSS architecture

## Quick Start

1. **Online Access**: Visit the [live demo](https://andyfenghaonan-arch.github.io/tf-heatmap-browser-full/)
2. **Select Parameters**:
   - Choose a transcription factor
   - Select ENCODE experiment ID
   - Pick chromosome (chr1-chr22)
   - Enter genomic position
3. **View Results**: Generate and explore Hi-ChIP heatmaps

## Usage

1. Select transcription factor from dropdown
2. Choose specific ENCODE dataset
3. Select chromosome of interest
4. Enter genomic coordinate (base pairs)
5. Click "Generate Heatmap" to visualize

## Supported Data

- **KLF4**: 1 dataset (ENCFF761ZKW)
- **NANOG**: 2 datasets (ENCFF153EHS, ENCFF926YZX)
- **OCT4**: 3 datasets (ENCFF003PEE, ENCFF259JPA, ENCFF906LPL)
- **RAD21**: 13 comprehensive datasets

## Technical Notes

- Each visualization covers 2MB genomic windows
- Data sourced from ENCODE Project Phase III
- Reference genome: GRCh38/hg38
- File format: PNG heatmap images
- Storage: ~12GB total dataset

## License

This project uses publicly available ENCODE data for research and educational purposes.
