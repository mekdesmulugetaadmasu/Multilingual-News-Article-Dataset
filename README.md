# Multilingual News Articles Dataset (By Mekdes Mulugeta & Dr. Michael Melese)

## Overview
This repository contains a dataset of **14,361 multilingual news articles** collected across five categories:

- **Politics**
- **Sports**
- **Health**
- **Business**
- **Technology**

The dataset is designed to aid in multilingual text classification, sentiment analysis, topic modeling, and other NLP tasks for low-resource languages. It consists of articles written in several languages, offering a diverse and rich source of news content for academic and industrial research purposes.

## Dataset Summary

| Category   | Number of Articles |
|------------|--------------------|
| Politics   | 3,000              |
| Sports     | 2,800              |
| Health     | 2,600              |
| Business   | 3,000              |
| Technology | 2,961              |
| **Total**  | **14,361**         |

## Structure of the Dataset

- The dataset is provided in a CSV format.
- Each record includes the following fields:
  - `id`: A unique identifier for each article.
  - `language`: The language of the article.
  - `category`: The category of the article (politics, sports, health, business, technology).
  - `title`: The title of the article.
  - `content`: The full text of the article.

### Prerequisites

To use the dataset in your machine learning projects:
1. Clone this repository:
   ```bash
   git clone https://github.com/mekdesmulugetaadmasu/multilingual-news-article-dataset.git

### Example Record:

```json
{
  "id": 12345,
  "language": "en",
  "category": "technology",
  "title": "The Future of Artificial Intelligence in 2024",
  "content": "Artificial Intelligence (AI) is expected to make significant advancements in..."
}

