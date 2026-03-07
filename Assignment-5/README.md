# DATA 622 – Homework 5

## Natural Language Processing: Text Summarization

### Overview

This assignment demonstrates different approaches to **text summarization** using Python and NLP libraries in Google Colab.
The goal is to compare **extractive, abstractive, and LLM-based summarization methods** on a real news article.

The article used in this assignment:
https://www.usatoday.com/story/news/politics/2025/06/13/pete-hegseth-pentagon-invade-greenland-plan/84188458007/

---

### Methods Implemented

The notebook implements the following summarization techniques:

1. **TextRank (Extractive Summarization)**
   Uses a graph-based ranking algorithm to identify the most important sentences in the article.

2. **Frequency-Based Sentence Scoring**
   Sentences are scored based on the frequency of important words.
   Sentences with higher scores are selected for the summary.

3. **Abstractive Summarization (Transformer Model)**
   Uses the pretrained **BART model** to generate a summary by rewriting the content in a shorter form.

4. **Lead-3 Baseline**
   A simple baseline method that selects the **first three sentences** of the article.

5. **Manual Compression Summary**
   Produces a summary by selecting approximately **20% of the original sentences**.

6. **LLM-Based Summary**
   Uses a pretrained instruction-following language model (**FLAN-T5**) to generate a summary from the article.

---

### Technologies Used

* Python
* Google Colab
* NLTK
* Sumy
* Transformers (HuggingFace)
* Newspaper3k

---

### Project Structure

```
DATA622-HW5/
│
├── DATA622_HW5.ipynb        # Main Google Colab notebook
├── README.md                # Assignment description
```

---

### How to Run the Notebook

1. Open the notebook in **Google Colab**.
2. Install the required libraries using the provided installation cell.
3. Run each cell sequentially.
4. The notebook will:

   * Download the news article
   * Process the text
   * Generate summaries using multiple methods

