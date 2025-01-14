## Legal Regulation of AI
## Description
This project aims to collect, pre-process, post-process, and structure second-instance decisions from the Court of Justice of the State of São Paulo (TJSP), using web scraping techniques.

## Project Structure
### 1. Data Collection

**scraping.r**: Scrapes decisions from the e-SAJ portal based on a list of search terms.

**Usage**: Enter your TJSP credentials to access the portal.

**Input**: termos_utilizados.xlsx (list of search terms).

**Output**: CSV file containing the scraped decisions.

### 2. Processing

**processing.py**: Cleans the texts, extracts relevant excerpts, and identifies cross-references between decisions.

**duplicates.py**: Generates, for each case, a list of other terms in which it appears.

## Data
**termos_utilizados.xlsx**: List of terms used for scraping.
