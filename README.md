# DNABERT-Enhancer_Portal

### Overview
The **DNABERT-Enhancer portal** offers an interactive platform to explore candidate **gain- and loss-of-function enhancer variants** predicted by the *DNABERT-Enhancer-350* model using **ENCODE SCREEN enhancers (350 bp)**.  
It also provides access to **genome-wide enhancer predictions** across the human reference genome (*GRCh38*).

This web application enables users to **visualize, search, and interpret enhancer regions** and their potential **functional impact in a genomic context**.

### Study layout
<img src="figures/Graphical_abstract.png" alt="DNABERT-Enhancer" width="600"/>

### Repository Structure
```
your-app/
│
├── app.py
├── requirements.txt
├── README.md
│
├── data/
│   └── whole_genome_prediction_data/
│       ├── WGP_1.csv
│       ├── WGP_2.csv
│       ├── WGP_3.csv
│       ├── WGP_4.csv
│       ├── WGP_5.csv
│       ├── Detailed_info_enhancer_GOF.csv
│       ├── Detailed_info_enhancer_LOF.csv
│       ├── Detailed_info_non-enhancer_GOF.csv
│       └── test.txt
│
├── figures/
│   ├── Enhancer.png
│   ├── Graphical_abstract.png
│   └── test.txt
```
