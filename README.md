# Quora-Questions-Classification-Using-Deep-Learning
- Predicted whether the questions were contextually sincere or insincere https://www.kaggle.com/c/quora-insincere-questions-classification .
- Pre-processing steps were performed to remove irrelevant details using Pandas library.
- Data Visualisation were created using Matplotlib, Seaborn for creating Wordcloud, Heatmap, Histogram, Bar Chart.
- Constructed a GloVe model to convert text to vector representation from Stanford's repository consisting of 840B tokens, 2.2M vocab, cased, 300d vectors, 2.03 GB size. https://nlp.stanford.edu/projects/glove/
- Performed a case study approach where four different model were created and their performances were than compared.
1. Traditional LSTM model
2. Bidirectional LSTM model using Recurrent Neural Network.
3. Bidirectional LSTM model using Convolutional Neural Network.
4. Fine-Tuned Bidirectional Encoder Representations from Transformers (BERT) model
- The dataset was highly imbalanced there the model was evaluated using F1-Score.
