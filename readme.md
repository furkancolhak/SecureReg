SecReg Dataset
--------------

### Overview

The SecReg Dataset is a curated collection of website URLs categorized as either benign (safe) or malicious. It was created by combining data from two primary sources: the Alexa 1m dataset and OpenPhish.

### Data Collection Process

1.  **Benign URLs**: Initially, we randomly selected safe website URLs from the Alexa 1m dataset.
    
2.  **Malicious URLs**: We gathered malicious URLs from OpenPhish.
    
3.  **Domain Extraction**: Using a WHOIS tool designed for open-source intelligence (OSINT), we extracted domain names from these URLs and removed their top-level domains (TLDs).
    
4.  **Duplicate Removal**: Duplicate domain names and those already present in the top 100k list on Alexa were eliminated to ensure data integrity.
    

### Data Distribution

The distribution of data in the SecReg Dataset is as follows:

|  | Benign | Malicious | Total |
| --- | --- | --- | --- |
| SecReg Dataset | 4,198 | 4,702 | 8,900 |
