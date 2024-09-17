\section{Transformer Architecture and Classification Models}

\subsection{Project Overview}

This repository is dedicated to exploring and implementing various machine learning models based on transformer architecture and other techniques for different classification tasks. The core of this project involves building a transformer architecture from scratch, inspired by the seminal paper, \textit{Attention is All You Need}.

\subsection{Contents}

\subsubsection{1. Transformer Architecture}

\begin{itemize}
    \item \textbf{Dot\_product\_Attention}: This file contains the general implementation of the transformer architecture. It includes the essential components as described in \textit{Attention is All You Need}. The implementation provides a foundation for understanding and experimenting with transformer models.
\end{itemize}

\subsubsection{2. Sentiment Analysis}

\begin{itemize}
    \item \textbf{Approaches Implemented}: The sentiment analysis task is approached through various models:
    \begin{itemize}
        \item Simple RNNs
        \item Bi-directional Encoder-Decoder LSTMs with additive attention
        \item Transformer encoder model
    \end{itemize}
    The performance of these models is evaluated, and results can be found \href{link-to-results}{here}.
\end{itemize}

\subsubsection{3. Multi-Class Classification Using BERT}

\begin{itemize}
    \item \textbf{Pre-trained BERT Model}: A pre-trained BERT model from the Hugging Face library is used for classifying consumer complaints. The dataset used is publicly available at \href{link-to-dataset}{gov.data}.
    \item \textbf{Categories}:
    \begin{itemize}
        \item Vehicle Loan
        \item Card
        \item Money Transfer
        \item Mortgage
        \item Debt Collection
        \item Savings Account
        \item Credit Report
        \item Loan
        \item Others
    \end{itemize}
    This task is inspired by the \href{link-to-project}{ProjectPro Multi-Class Classification project}. Detailed implementation and results can be found \href{link-to-results}{here}.
\end{itemize}

\subsection{Installation and Usage}

To get started with this project, follow these steps:

\begin{enumerate}
    \item \textbf{Clone the Repository}:
    \begin{verbatim}
    git clone https://github.com/yourusername/transformer-classification.git
    cd transformer-classification
    \end{verbatim}
    
    \item \textbf{Install Dependencies}:
    Ensure you have Python 3.7+ and install the required packages:
    \begin{verbatim}
    pip install -r requirements.txt
    \end{verbatim}
    
    \item \textbf{Run the Models}:
    \begin{itemize}
        \item For transformer architecture and attention mechanisms, execute:
        \begin{verbatim}
        python dot_product_attention.py
        \end{verbatim}
        
        \item For sentiment analysis, navigate to the relevant script and run:
        \begin{verbatim}
        python sentiment_analysis.py
        \end{verbatim}
        
        \item For multi-class classification using BERT, execute:
        \begin{verbatim}
        python bert_classification.py
        \end{verbatim}
    \end{itemize}
\end{enumerate}

\subsection{References}

\begin{itemize}
    \item \textit{Attention is All You Need} - Vaswani et al. \href{https://arxiv.org/abs/1706.03762}{Link to Paper}
    \item \href{link-to-project}{ProjectPro Multi-Class Classification}
\end{itemize}

\subsection{License}

This project is licensed under the MIT License. See the \href{LICENSE}{LICENSE} file for details.

\subsection{Contact}

For any questions or suggestions, please feel free to reach out to \href{mailto:your-email@example.com}{your-email@example.com}.


















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
