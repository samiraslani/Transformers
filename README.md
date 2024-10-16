# Transformer Architecture and Classification Models

## Project Overview

This repository is dedicated to exploring and implementing various machine learning models based on transformer architecture. The core of this project involves building a transformer architecture from scratch, inspired by the seminal paper, *Attention is All You Need*. We will then implement the transformer's model on various tasks such as sentiment analysis, multi-class classification, and machine translation. 

## Contents

### 1. Transformer Architecture

The file [Dot_product_Attention](Dot_product_Attention.ipynb/) contains the general implementation of the transformer architecture. It includes the essential components as described in *Attention is All You Need*. The implementation provides a foundation for understanding and experimenting with transformer models.

### 2. Sentiment Analysis
A transformer encoder is used to run a sentiment analysis on Canva customer feedbacks. The sentiments include positive and negative (binary classification). This model has about 13,000 trainable parameters; the accuracy is 97% and 91% on the training and testing sets respectively. The code can be found [here](Sentiment-DotAtten.ipynb/).

### 3. Multi-Class Classification 

-**Using Pre-trained BERT Model**: A pre-trained BERT model from the Hugging Face library is used for classifying consumer complaints. The dataset used is publicly available at [gov.data](https://catalog.data.gov/dataset/consumer-complaint-database).

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

  -** A Small Encoder Model**: This model has a maximum of 4 million parameters to train and reaches an accuracy of 67%, average percision of 64/100, and recall score of 63/100 on the testing set. More detailed results can be found [here](complaints+attention_encoder.ipynb/)

  ### 4. Machine Translation
  This project consists of a full transformer model that translates various human-readable dates to machine-readable dates (YYYY-MM-DD). The accuracy reaches 96% on both the training and testing sets. For a more detailed look please visit [here](Dot_machine_translation.ipynb/). 

## Installation and Usage

To get started with this project, follow these steps:

1. **Clone the Repository**:

   ```bash
   git clone https://github.com/samiraslani/Transformers.git

## References

- *Attention is All You Need* - Vaswani et al. [Link to Paper](https://arxiv.org/abs/1706.03762)
- [ProjectPro Multi-Class Classification](https://www.projectpro.io/project-use-case/nlp-project-for-multi-class-text-classification-using-bert)

## License

This project is licensed under the MIT License. See the [LICENSE](https://opensource.org/license/mit) file for details.

## Contact

For any questions or suggestions, please feel free to reach out to [shirinamiraslani@gmail.com](mailto:shirinamiraslani@gmail.com).
