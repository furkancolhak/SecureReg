SecReg Dataset
--------------

### Overview

We gathered data from two different sources to create our dataset. Initially, we obtained benign (safe) website URLs from the Alexa 1m dataset by randomly selecting them. Then, we gathered malicious URLs from OpenPhish. Using a WHOIS tool designed explicitly for open-source intelligence (OSINT), we extracted domain names from these URLs and removed their top-level domains (TLDs). Subsequently, we eliminated duplicate domain names and those already present in the top 100k list on Alexa. This step was crucial as we utilized the Alexa top 100k list as a fictional database of registrants. 

### Data Distribution

The distribution of data in the SecReg Dataset is as follows:

|  | Benign | Malicious | Total |
| --- | --- | --- | --- |
| SecReg Dataset | 4,198 | 4,702 | 8,900 |
