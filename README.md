# Transformer Architecture and Classification Models

## Project Overview

This repository is dedicated to exploring and implementing various machine learning models based on transformer architecture. The core of this project involves building a transformer architecture from scratch, inspired by the seminal paper, *Attention is All You Need*. We will then implement the transformer's model on various tasks such as sentiment analysis, multi-class classification, and machine translation. 

## Contents

### 1. Transformer Architecture

- **Dot_product_Attention**:

The file [Dot_product_Attention](Dot_product_Attention.ipynb/) contains the general implementation of the transformer architecture. It includes the essential components as described in *Attention is All You Need*. The implementation provides a foundation for understanding and experimenting with transformer models.

### 2. Sentiment Analysis

- **Approaches Implemented**: The sentiment analysis task is approached through various models:
  - Simple RNNs
  - Bi-directional Encoder-Decoder LSTMs with additive attention
  - Transformer encoder model

  The performance of these models is evaluated, and results can be found [here](Sentiment-DotAtten.ipynb/).

### 3. Multi-Class Classification Using BERT

- **Pre-trained BERT Model**: A pre-trained BERT model from the Hugging Face library is used for classifying consumer complaints. The dataset used is publicly available at [gov.data](https://catalog.data.gov/dataset/consumer-complaint-database).

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
