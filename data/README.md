# Data Folder Overview

This folder contains the datasets used in the paper. Below is a description of the main subfolders and their contents:

## HAVOC/
- **havoc.tsv**: The main HAVOC dataset, containing prefixes sampled web-scale datasets (Common Crawl, C4 and Fine Web). The prefix column contains the main prefixes, the suffix contains the original sentence. You can refer to "PrefixLab" to get the labels of "Hate and Violence (H)", "Ideological Harm (IH)", "Sexual (SE)", "Illegal Activities (IL)" and "Self Inflicted (SI)" harms respectively. Please have a look at the paper to know more about the harms.
- **havoc_modeleval.tsv**: This file contains the prefix responses on various models, and the response annotations by TTP.

## TTP-Eval/
- **TTPEval.tsv**: The primary evaluation set for TTP (Topical and Toxic Prompt), containing web pages and their annotations.
- **TTP_Performance_On_TTPEval.tsv**: Results or performance metrics of various models evaluated on the TTP-Eval set.

---

Please note that we have used "intent" as the label instead of "toxic" internally. Each dataset is provided in TSV (Tab-Separated Values) format for easy loading and processing.

Please have a look at the paper to get more idea about the datasets.