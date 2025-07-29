# 💊 VigiMed
This project aims to centralize the ingestion, processing, compression, and visualization of [VigiMed](https://dados.anvisa.gov.br/dados/) data in Brazil. It focuses on geographic, temporal, and operational analysis to support public health decision-making.
 
# 🌳  Project Folder Overview

```bash
dengue/
├── config/                    # Configuration files (e.g., parameters, paths, credentials)
│   └── README.md              # Description of config usage and structure
├── dashboard/powerbi/         # Power BI dashboards and reports
│   └── README.md              # Notes about the visualizations and how to use them
├── data/                      # Data storage, organized by processing layer
│   └── staging/               # Temporary zone for data loading and testing
│   ├── bronze/                # Raw data as collected from external sources
│   ├── silver/                # Cleaned and transformed data
│   ├── gold/                  # Aggregated and enriched data for analytics
│   └── README.md              # Data pipeline documentation
├── docs/                      # Project documentation
│   └── README.md              # General documentation and onboarding instructions
├── root/                      # Root-level utilities for project setup or orchestration
│   ├── README.md              # Introductory README for the repository
│   └── requirements.txt       # Python dependencies required for the project
├── src/                       # Source code for data ingestion, processing, and helpers
│   ├── cnes/                  # Scripts to process CNES (National Registry of Health Facilities) data
│   ├── vigimed/               # Scripts to process Vigimed (Notifiable Diseases) data
│   └── utils/                 # Utility functions and tools
│       └── compression_for_parquet.py  # Function to split large Parquet files into chunks
├── tests/                     # Unit and integration tests
│   └── README.md              # Test guidelines and coverage notes
```
