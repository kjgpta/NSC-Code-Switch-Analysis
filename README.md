# NSC Code-Switch Analysis

This repository contains code and resources for performing code-switching analysis using the NSC (National Speech Corpus) dataset. Code-switching refers to the phenomenon of mixing two or more languages within a single conversation or utterance. The goal of this project is to provide tools and techniques for analyzing code-switching patterns and understanding the linguistic characteristics of code-switched speech.

This work has been published in the [International Conference on Asian Language Processing 2023](https://www.colips.org/conferences/ialp2023/wp/) which can be found [here](https://ieeexplore.ieee.org/abstract/document/10337279).

## Introduction

Code-switching is a prevalent linguistic behavior in multilingual communities. It can occur for various reasons, including social, cultural, or contextual factors. Understanding code-switching patterns is crucial for language researchers, sociolinguists, and natural language processing (NLP) practitioners. This repository provides code and resources to facilitate the analysis of code-switched speech using the NSC dataset.

## Installation

To use the code and scripts in this repository, please follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/kjgpta/NSC-Code-Switch-Analysis.git
   ```

2. Install the required dependencies. You can use `pip`:

   ```bash
   pip install -r requirements.txt
   ```

3. Setup any additional configuration or environment variables as necessary.

## Usage

This section describes how to use the code and scripts provided in this repository.

1. Normalizing Data:

   The `Normalizing Data` directory contains scripts for cleaning and preparing the NSC dataset for analysis. This includes tasks such as data cleaning, normalization.

2. POS Analysis:

   The `POS Analysis` directory contains scripts for conducting code-switching analysis to predict code-switching behavior using Part-of-Speech. These involve the Wordwise and Pairwise analysis of the CS data.

Please refer to the individual directories for detailed instructions on how to run each script or module.

## Data

The NSC dataset used in this project is not public and thus is not included in this repository. However, you can request IMDA Singapore to get the same. Once you have obtained the dataset, make sure to follow the preprocessing steps described in the repository to prepare the data for analysis.

## Acknowledgement
This research is supported by the Ministry of Education, Singapore, under its Academic Research Fund Tier 2(MOE2019-T2-1-084). Any opinions, findings and conclusions or recommendations expressed in this material are those of the author(s) and do not reflect the views of Ministry of Education, Singapore.

## License

This project is licensed under the [CC0-1.0 License](LICENSE).
