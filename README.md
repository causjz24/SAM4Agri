# SAM4AgriRS-Monitoring

The literature dataset for a systematic review of Segment Anything Model (SAM) applications in agricultural remote sensing monitoring.

## Overview

This repository provides the literature metadata used in the review:

> **SAM in Agricultural Remote Sensing: Applications, Challenges, and Prospects**

The dataset summarizes studies applying SAM and its variants to agricultural remote sensing monitoring tasks.The current dataset contains **199 literature records**, with publication dates ranging from **March 2023 to June 2026**.


## Dataset

The main dataset is available at:

```text
SAM for Agricultural Remote Sensing Monitoring Literature Dataset.xlsx
```

The Excel workbook contains seven worksheets:

| Worksheet | Application domain | Number of records |
|---|---|---:|
| Field | Field parcels and field boundaries | 34 |
| Road | Field roads and road networks | 14 |
| Crop | Crops, organs, phenotypes, and crop mapping | 77 |
| Pests and diseases | Agricultural pests and diseases | 15 |
| Livestock | Livestock and poultry monitoring | 14 |
| Forests and trees | Forests, trees, and individual crowns | 31 |
| Aquaculture | Aquaculture facilities and aquatic animals | 14 |
| **Total** |  | **199** |

## Data Fields

Each worksheet contains the following bibliographic fields:

| Field | Description |
|---|---|
| Item Type | Publication type |
| Author | Authors of the study |
| Title | Article or conference paper title |
| Publication Title | Journal or conference name |
| ISBN | International Standard Book Number, where available |
| ISSN | International Standard Serial Number, where available |
| DOI | Digital Object Identifier |
| Abstract | Abstract of the publication |
| Publication Date | Publication date |
| Pages | Page range or article number |
| Issue | Journal issue |
| Volume | Journal volume |
| Country | Country of the first author's affiliation |

## Repository Structure

```text
SAM4AgriRS-Monitoring/
├── README.md
└── SAM for Agricultural Remote Sensing Monitoring Literature Dataset.xlsx
```

## Recommended Use

The dataset can be used to:

- reproduce the descriptive and bibliometric analyses reported in the review;
- examine the distribution of SAM applications across agricultural domains;
- compare publication sources, countries, years, and research topics;
- support updates and extensions of the literature review.

## Data Updates and Living Review

To maintain the timeliness and long-term value of this resource, the dataset will be updated as new studies on SAM and its variants in agricultural remote sensing monitoring are published. Through these regular updates, the review is intended to function as a **living review**, continuously reflecting the latest research progress, technical developments, and application trends in the field.

Each update will include:

- an updated literature search covering studies published since the previous release;
- screening and classification of newly identified studies using the same inclusion criteria and application-domain framework;
- revision of the total number of included records and domain-specific statistics;
- correction of bibliographic information and classifications where necessary;
- documentation of the literature search cutoff date;
- a summary of additions, removals, and other changes relative to the previous release;
- a new version number and release date.

Major updates that substantially change the analytical results, classification framework, or conclusions of the review will be documented separately in the release notes. Earlier dataset versions will remain archived to support transparency, reproducibility, and longitudinal comparison.
