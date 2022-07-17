# eBay NER Machine Learning Challenge

NER labeling for handbag dataset

Baseline F1 Score to beat: 0.800

## Model 2.3
Method - 2 Bidirectional LSTMs for main
       - Time Distributed LSTM to capture character positioning
Inputs - Word Embeddings, POS embeddings, Character encoding from LSTM
Tags - Retagged with BIOS tags for multi-token
Data - Training set + random expansion

Model Params - 12,852,467
epochs - 10

Result - F1 Score: 0.82313


## Model 2.2
Method - 2 Bidirectional LSTMs
Inputs - Word Embeddings and POS embeddings
Tags - Retagged with BIOS tags for multi-token
Data - Training set + random expansion

Model Params - 12,708,947
epochs - 12

Result - F1 Score: 0.8149

