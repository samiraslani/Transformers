# Transformer Architecture and Classification Models

## Project Overview

This repository is dedicated to exploring and implementing various machine learning models based on transformer architecture. The core of this project involves building a transformer architecture from scratch, inspired by the seminal paper, *Attention is All You Need*. We will then implement the transformer's model on various tasks such as sentiment analysis, multi-class classification, and machine translation.

The repository includes models built with both **TensorFlow/Keras** and **PyTorch**. The following sections provide an overview of each implementation and the associated tasks.

## Contents

### TensorFlow/Keras Projects

These projects are implemented using the **TensorFlow** and **Keras** libraries.

#### 1. Transformer Architecture
The file [Dot_product_Attention](Dot_product_Attention.ipynb/) contains the general implementation of the transformer architecture. It includes the essential components as described in *Attention is All You Need*. The implementation provides a foundation for understanding and experimenting with transformer models.

#### 2. Sentiment Analysis
A transformer encoder is used to run sentiment analysis on Canva customer feedback. The sentiments include positive and negative (binary classification). This model has about 13,000 trainable parameters, achieving 97% accuracy on the training set and 91% accuracy on the test set. The code can be found [here](Sentiment-DotAtten.ipynb/).

#### 3. Multi-Class Classification
- **Using Pre-trained BERT Model**: A pre-trained BERT model from the Hugging Face library is used for classifying consumer complaints. The dataset is publicly available at [gov.data](https://catalog.data.gov/dataset/consumer-complaint-database).

  **Categories**:
  - Vehicle Loan
  - Card
  - Money Transfer
  - Mortgage
  - Debt Collection
  - Savings Account
  - Credit Report
  - Loan
  - Others

  This task is inspired by the [ProjectPro Multi-Class Classification project](https://www.projectpro.io/project-use-case/nlp-project-for-multi-class-text-classification-using-bert). Detailed implementation and results can be found [here](bert.ipynb/).

- **A Smaller Encoder Model**: The same multi-class classification task is done by a smaller encoder model with a maximum of 4 million parameters, achieving 67% accuracy, 64% precision, and 63% recall on the test set. Detailed results are available [here](complaints+attention_encoder.ipynb/).

#### 4. Machine Translation
This project consists of a full transformer model that translates human-readable dates into machine-readable dates (YYYY-MM-DD format). The model achieves 96% accuracy on both training and test sets. For a more detailed look, please visit [here](Dot_machine_translation.ipynb/).

### PyTorch Projects

These projects are implemented using the **PyTorch** library.

#### 1. **French to English Machine Translation (fra_eng_translation)**
This project implements a transformer-based model in **PyTorch** for translating French text to English. The dataset used for this task is taken from the book *Learning Deep Learning: Theory and Practice of Neural Networks, Computer Vision, Natural Language Processing, and Transformers Using TensorFlow* (ISBN: 9780137470358) and the video series *Learning Deep Learning: From Perceptron to Large Language Models* (ISBN: 9780138177553) by Magnus Ekman. For more information please visit [here](https://github.com/NVDLI/LDL/).

You can find the code for this model in [fra_eng_translation](fre_eng_translation.ipynb/).

---

---

## Installation and Usage

To get started with this project, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/samiraslani/Transformers.git

   ## References

- *Attention is All You Need* - Vaswani et al. [Link to Paper](https://arxiv.org/abs/1706.03762)
- [ProjectPro Multi-Class Classification](https://www.projectpro.io/project-use-case/nlp-project-for-multi-class-text-classification-using-bert)
- Dataset for French-English Machine Translation: From the book *Learning Deep Learning: Theory and Practice of Neural Networks, Computer Vision, Natural Language Processing, and Transformers Using TensorFlow* (ISBN: 9780137470358) and the video series *Learning Deep Learning: From Perceptron to Large Language Models* (ISBN: 9780138177553) by Magnus Ekman.

## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.

## Contact

For any questions or suggestions, please feel free to reach out to [shirinamiraslani@gmail.com](mailto:shirinamiraslani@gmail.com).

