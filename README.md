# Multilingual Sentiment Classification with BERT

This project demonstrates fine-tuning a BERT-based multilingual model for sentiment classification across multiple languages using the **Amazon Reviews Multilingual dataset**. The notebook explores different transfer learning approaches, including zero-shot, few-shot, training transfer, and test transfer methods, comparing their performance on diverse language datasets.

# Project Overview
- Goal: Fine-tune a multilingual model to classify product reviews as positive or negative across multiple languages.
- Dataset: Amazon Reviews Multilingual.
- Model: BERT-multilingual.
- Reference:[2020.emnlp-main.369.pdf](https://github.com/user-attachments/files/18322619/2020.emnlp-main.369.pdf)

# How to Run the Notebook
1. Clone this repository:
```bash
git clone https://github.com/Hazel1763/Projects.git
```
2. Install the required packages:
```bash
pip install -r requirements.txt
```
3. Open the notebook and run cells to reproduce the results.  
⚠️ Note: A **GPU environment** is recommended to reduce runtime.

# Future Improvements
- Explore additional transfer learning techniques (e.g. data augmentation, back-translation).
- Increase test sample size in generative models to enhance the robustness of performance comparisons.
- Evaluate performance on more languages, especially low-resource languages.

# Acknowledgments
- The amazon_reviews_multi dataset used in this project is sourced from the Hugging Face datasets library, based on the publicly available Amazon product reviews dataset.
- The bert-base-multilingual-cased model used in this project is provided by Hugging Face Model Hub, originally developed by Google AI.

# Contact
If you have any questions or suggestions, feel free to reach out.



