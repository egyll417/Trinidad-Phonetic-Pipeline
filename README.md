# Trinidadian Creole: A Mixed-Methods Linguistic Analysis

## Project Overview
This repository contains a comprehensive project for analyzing Trinidadian Creole. It bridges the gap between raw acoustic measurements and sociolinguistic context by utilizing both Signal Processing and Natural Language Processing (NLP).

## Project Components

### 1. Phonetic Pipeline (Acoustic Analysis)
**File:** `Trinidad_Phonetic_Pipeline.ipynb`
* **Focus:** Quantitative analysis of rhoticity (r-sounds) in Trini Creole.
* **Methods:** Uses acoustic data derived from Praat to visualize phonological shift across speech communities.
* **Goal:** To identify patterns of rhotic intrusion or deletion in high-contact vs. conservative dialects.



### 2. Sociolinguistic Context Miner (NLP)
**File:** `Trinidad_Sociolinguistic_Miner.ipynb`
* **Focus:** Automated literature review and metadata extraction.
* **Methods:** Utilizes spaCy (Named Entity Recognition) and BeautifulSoup to scrape and process research text.
* **Goal:** Automatically identifies key languages, ethnic groups (NORP), and historical hubs (GPE) mentioned in Creole research to provide historical context for the phonetic findings.



---

## Research Automation & Scalability
A key feature of this project is its **scalability**. The NLP architecture developed for the "Context Miner" is designed to be domain-agnostic. 

By adjusting the Named Entity Recognition (NER) filters, this tool can be adapted for broder uses, such as medical data mining, significantly reducing manual data collection time in a research environment.

## Tech Stack
* **Linguistic Tools:** Praat, spaCy (NLP)
* **Data Science:** Pandas, Matplotlib, Seaborn
* **Automation:** BeautifulSoup, Requests
