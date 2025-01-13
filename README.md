# NLP_Practice

## Overview
The **NLP_Practice** directory serves as a centralized repository for all my projects involving Natural Language Processing (NLP). Each folder within this directory represents a unique project that showcases specific NLP techniques, methodologies, and use cases. 

---

## Current Projects

### 1. Article_Feature_Extraction
#### Description
This project focuses on processing a dataset of article URLs to extract structured data and perform Named Entity Recognition (NER). It is divided into two key components:
1. **Feature Extraction**:
   - Extracts article attributes such as the news source, header, body text, and authors from the URLs.
   - Outputs a structured Excel file for further processing.
2. **Entity Extraction**:
   - Uses the structured data to identify named entities like people, organizations, and locations through spaCy's NER capabilities.

#### Files
- **Article_Feature_Extraction.ipynb**: Notebook for extracting features from articles.
- **Entity_Extraction.ipynb**: Notebook for performing NER on the structured data.
- **Input/Output Files**:
  - `articles.xlsx` (input): Contains a column `URL` with links to articles.
  - `prepared_articles.xlsx` (output): Structured file ready for NER.
  - `entities_extracted.xlsx` (output): Final file enriched with extracted entities.

#### Key Features
- Processes raw article data into structured formats.
- Applies advanced NLP techniques for named entity recognition.
- Modular pipeline for scalability.

#### Technologies
- **Python 3.8+**
- Libraries:
  - `pandas`, `requests`, `numpy`
  - `BeautifulSoup` (from `bs4`)
  - `spaCy` (requires `en_core_web_sm` language model)

#### Usage
1. Clone the repository:
   ```bash
   git clone https://github.com/mpdaniels414/NLP_Practice.git
   cd NLP_Practice
