# NEXON Open API Game Trade Data Collection & Analysis

🌐 [한국어](README.md) | **English**

This project automatically collects game trade data from the NEXON Open API and analyzes the collected data.

- Collection pipeline: [notebooks/01_collection](notebooks/01_collection/README.en.md)
- Analysis: notebooks/02_analysis (planned)

## Repository Structure

```
nexon-api-collector/
├── .github/
│   └── workflows/
│       ├── mabinogi.yml             # Mabinogi auction collection workflow
│       └── mabinogi_heroes.yml      # Mabinogi Heroes marketplace and notice workflow
├── notebooks/
│   ├── 01_collection/
│   │   ├── mabinogi_collect.ipynb          # Mabinogi collection, loading, deduplication
│   │   ├── mabinogi_heroes_collect.ipynb   # Mabinogi Heroes collection, loading, deduplication
│   │   ├── README.md                       # Collection pipeline (Korean)
│   │   └── README.en.md                    # Collection pipeline (English)
│   └── 02_analysis/                 # Analysis of collected data (planned)
├── requirements.txt
├── .gitignore
├── README.md
└── README.en.md
```