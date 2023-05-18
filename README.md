# NSC Code-Switch Analysis

This repository contains code and resources for performing code-switching analysis using the NSC (National Speech Corpus) dataset. Code-switching refers to the phenomenon of mixing two or more languages within a single conversation or utterance. The goal of this project is to provide tools and techniques for analyzing code-switching patterns and understanding the linguistic characteristics of code-switched speech.

## Introduction

Code-switching is a prevalent linguistic behavior in multilingual communities. It can occur for various reasons, including social, cultural, or contextual factors. Understanding code-switching patterns is crucial for language researchers, sociolinguists, and natural language processing (NLP) practitioners. This repository provides code and resources to facilitate the analysis of code-switched speech using the NSC dataset.

## Installation

To use the code and scripts in this repository, please follow these steps:

1. Clone the repository:

   ```bash
   git clone https://github.com/kjgpta/NSC-Code-Switch-Analysis.git
   ```

2. Install the required dependencies. You can use either `pip` or `conda`:

   ```bash
   pip install -r requirements.txt
   ```

3. Setup any additional configuration or environment variables as necessary.

## Usage

This section describes how to use the code and scripts provided in this repository.

1. Normalizing Data:

   The `Normalizing Data` directory contains scripts for cleaning and preparing the NSC dataset for analysis. This includes tasks such as data cleaning, normalization, segmentation, and annotation.

2. Categorical Analysis:

   The `Categorical Analysis` directory contains code for extracting the information about the categories of the CS data. These features may include linguistic, acoustic, or contextual information that can be used for analysis.

3. POS Analysis:

   The `POS Analysis` directory contains scripts for conducting code-switching analysis and building models to predict code-switching behavior using Part-of-Speech. These involve the Wordwise and Pairwise analysis of the CS data.

Please refer to the individual directories for detailed instructions on how to run each script or module.

## Data

The NSC dataset used in this project is not public and thus is not included in this repository. However, you can request IMDA Singapore to get the same. Once you have obtained the dataset, make sure to follow the preprocessing steps described in the repository to prepare the data for analysis.

## License

This project is licensed under the [CC0-1.0 License](LICENSE). Feel free to modify and use the code according to the terms of the license.