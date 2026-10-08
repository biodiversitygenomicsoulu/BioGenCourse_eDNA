# BioGenCourse_eDNA
eDNA sequence data and analyses comparing filtration methods and extraction protocols for biomonitoring of vertebrate taxa
[![DOI](https://zenodo.org/badge/1278931184.svg)](https://doi.org/10.5281/zenodo.23240917)

Raw sequences are deposited in the National Center for Biotechnology Information’s Sequence Read Archive (BioProject: PRJNA1541148). 

```
├── data/
│   ├── raw/               # Metadata and eDNA read table output from Apscale_Nanopore
│   └── processed/         # Decontaminated OTU tables, long-format data, resulting tables from ordination analyses
├── results/
│   ├── figures/           # Figures for manuscript and analyses
│   ├── tables/            # Table results: upset plot
├── mibird diversity analysis.Rmd
├── teleo diversity analysis.Rmd
├── combined diversity analysis.Rmd
├── upset_method.Rmd
└── README.md
```

| Step | File | Description | 
|------|------|-------------|
| 1 | mibird diversity analysis.Rmd | imports MiBird otu table, filters samples, decontaminates with microDecon, runs community analysis | 
| 2 | teleo diversity analysis.Rmd | imports Tele02 otu table, filters samples, decontaminates with microDecon, runs community analysis |
| 3 | combined diversity analysis.Rmd | produces main text figures with combined results from both MiBird and Tele02 datasets | 
| 4 | upset_method.Rmd | runs UpSet analysis and produces method-specific UpSet plot  | 

## Citation
Please cite the associated manuscript when using these data.

## Maintainer

**Patrick Nichols**  
Postdoctoral Researcher  
Biodiversity Genomics Research Group  
University of Oulu  
📧 patrick.nichols@oulu.fi  
🔗 https://biodiversitygenomics.org/
