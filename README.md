# Transformers
 In this project, we aim to build a transformer's architecture from scratch. The file [Dot_product_Attention](Dot_product_Attention.ipynb/) contains a general code for a transformer's architecture and is based on the paper [Attention is All you Need.](https://arxiv.org/abs/1706.03762)
 
 The transformer's code is then implemented for various tasks as the following: 
 
 * **Sentiment Analysis**:
   
   Several approaches for this task are already implemented from applying simple RNNs to bi-directional encoder decoder LSTMs equipped with [additive attention](https://github.com/samiraslani/Additive-Attention-model). The task of sentiment analysis is also examined with a transformer encoder model. The results can be found [here](Sentiment-DotAtten.ipynb/)

 * **Multi-Class Classification Using BERT Model**:
   Loaded a pre-trained BERT model from Hugging-Face library.
   The dataset is publicly available at [gov.data](https://catalog.data.gov/dataset/consumer-complaint-database).
   The goal is given the consumer complaint, the model classifies the complaint into one of the following categories:
   - vehicle_loan
   - Card
   - Money_transfer
   - Mortgage
   - Debt_collection
   - Savings account
   - Credit_report
   - Loan
   - Others
This project is inspired by ProjectPro Multi-Class Classification project. More information can be found [here](https://www.projectpro.io/project-use-case/nlp-project-for-multi-class-text-classification-using-bert)

# Add references. 
