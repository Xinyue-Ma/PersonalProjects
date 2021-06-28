# Literature Review

## NLP Application in Finance
Market Analysis: Apply classification/clustering method to analyze market

- Micro: Stock price prediction

- Macro: Market movement

Risk Management: Apply classification method to detect fraud or defaults

Compliance: Apply various NLP methods to verify compatibility to internal investment/loan rule

Asset Management: Apply various NLP methods to organize unstructured documents

- Internal: Utilize internal documents

- External: Utilize internal documents like SNS etc

Customer Engagement: Apply Question Answering, Dialog to communicate with customer

## Literatures

### [Bidirectional LSTM](https://www.ijcai.org/Proceedings/2020/0631.pdf)

Financial Risk Prediction with Multi-Round Q&A Attention Network

- Extract features of each round of dialogue through a bidirectional attention mechanism and predict the volatility after the earnings conference call events.

- Advantages: the model significantly outperforms the previous state-of-the-art methods and other baselines.

- Disadvantages: costly compared to LSTM

### []()

FinBERT: A Pretrained Language Model for Financial Communications

- A BERT model pre-trained on financial communication text

- Advantages: can be used by applications where the prediction target goes beyond sentiment, such as financial-related outcomes including stock returns, stock volatilities, corporate fraud, etc. It improves the performance.

- Disadvantage: computational resources intensive

###

Financial Event Extraction Using Wikipedia-Based Weak Supervision

- Use weak supervision approach to identify events related to a given company, and identify sentences containing events that would be of interest to the analyst. Wiki dataset is based on weak labels, and SentiFM is based on manual annotation.

- Advantages: no requirement for knowledge base of events

- Disadvantages: improvement on extracting events without companies’ names mentioned

###
Stock Embeddings Acquired from News Articles and Price History, and an Application to Portfolio Optimization

- Using stock embedding to acquire such vectors from stock price history and news articles by using a neural network framework. the stock embedding detects news articles that are related to the stock.

- Advantages: Stock embedding can be applied to other tasks besides price movement classification, such as portfolio management, risk control and asset pricing.

###
Modeling the Stock Relation with Graph Network for Overnight Stock Movement Prediction

- Predict the overnight stock price movement based on the overnight news that take place during the stock market closing time. Since using the relational graph convolutional network, the proposed network is able to predict the movement of stocks that is not directly associated with news. 

- Advantages: outperform the strong baselines






