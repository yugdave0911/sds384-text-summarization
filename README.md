# Text Summarization using Deep Learning
### Members: Aditya Anekar, Jaimik Patel, Srishti Shankar, Yug Dave

## Project Description:

This project focuses on text summarization using deep learning techniques applied to scientific papers. The primary goal is to develop models capable of automatically generating concise and informative summaries of scientific articles. By leveraging deep learning algorithms, the project aims to extract key information from lengthy texts efficiently, facilitating faster comprehension and aiding researchers in identifying relevant literature.

## Goals:

1. Implement deep learning models for text summarization.
2. Train models on scientific paper datasets to generate accurate summaries.
3. Evaluate model performance using standard evaluation metrics such as ROUGE and BLEU.
4. Explore potential applications of text summarization in scientific research and literature review processes.

## Data:

The data used in this project is sourced from the Hugging Face Datasets library, specifically the "scientific_papers" dataset. The dataset contains a collection of scientific papers across various domains, including computer science, biology, physics, and more. Each paper includes data such as 'article' i.e. the full text, 'abstract' i.e. the summary and 'section_names'. The dataset is suitable for training and evaluating text summarization models tailored for scientific literature.

### Information about the Data:

- **Format:** JSON
- **Fields:** Each entry in the dataset contains fields such as "article", "abstract", "section_names"
- **Size:** The dataset comprises a substantial number of scientific papers across different disciplines however only a subset (pubmed) of the dataset was used for the project, providing ample data for training and testing text summarization models. An even smaller sub-subset was used for model training and evaluation due to computational limitations.
- **Preprocessing:** Data preprocessing involves tasks such as tokenization, sentence segmentation, and cleaning to prepare the text for model input.

### Models
The finetuned [T5](https://huggingface.co/jaimik69/t5-small-pubmed) and [BART](https://huggingface.co/jaimik69/bart-base-pubmed) models are available on Huggingface platform

## References:

1. The Hugging Face Datasets Library: [https://huggingface.co/datasets](https://huggingface.co/datasets)
2. Lewis, M., Liu, Y., Goyal, N., Ghazvininejad, M., Mohamed, A., Levy, O., ... & Zettlemoyer, L. (2020). Bart: Denoising sequence-to-sequence pre-training for natural language generation, translation, and comprehension. arXiv preprint arXiv:1910.13461.
3. Vaswani, A., Shazeer, N., Parmar, N., Uszkoreit, J., Jones, L., Gomez, A. N., ... & Polosukhin, I. (2017). Attention is all you need. In Advances in neural information processing systems (pp. 5998-6008).
