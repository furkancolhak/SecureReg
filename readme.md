Overview

This repository contains the datasets utilized in a research project focused on developing and evaluating a model for malicious domain detection. The datasets were meticulously curated to ensure data quality, impartiality, and comprehensive representation.
Datasets
1. Malicious Domain Dataset

The primary dataset comprises domain names obtained from the OpenPhish platform, which releases a compilation of 500 malicious URLs every 12 hours. The dataset originally contained 50,000 URLs, which were reduced to 12,000 unique domain names. After removing duplicate entries, the dataset was refined to a total of 10,000 distinct malicious domain names.
2. Benign Domain Dataset

To provide a balanced perspective, the research includes a dataset of 10,000 benign domain names. These were meticulously selected from the Alexa dataset, ensuring representation from the most recent 100,000 randomly sampled domains within the extensive AlexaTop1M dataset. This strategic selection aimed to prevent skewing or overrepresentation of exceptionally well-performing domains in the upper strata of the Alexa rankings.
3. AlexaTop100k Dataset

This dataset serves a pivotal role in the research as a fictional registration domain database. It consists of common domain names, strategically chosen to facilitate the identification of similarities with newly registered domains. The selection of the AlexaTop100k dataset is based on its representation of prevalent and widely used domain names, making it an apt resource for simulating domain registration patterns.
Data Preprocessing

To streamline and refine the datasets, all top-level domains (TLDs) were systematically excluded. This step aimed to eliminate unnecessary variations and standardize the dataset, focusing the analysis on the core domain names. Additionally, the removal of duplicate entries was performed to ensure the integrity and uniqueness of the dataset.
Usage

Researchers and practitioners interested in malicious domain detection can utilize these datasets for training and evaluating models. The careful curation process underscores the significance of data quality and impartiality, contributing to the robustness and credibility of the research findings.
