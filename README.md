# AIDI1002_Final_Project
Sentiment Classification using BERT and DistilBERT(AIDI 1002 Final Project)
Group Members:
Kusum Kumari and Ashley Sherry Kombarakaran Antony Babu

1.PROJECT OVERVIEW
This project replicates the methodology from the research paper:
"BERT: Pre-training of Deep Bidirectional Transformers for Lnaguage Understanding"(Devlin et al.,2019)
We executed the BERT model for sentiment analysis on the IMDB Movie Review Dataset and in addition we added our contirbution by training and analyzing a second model: DistilBERT, an easy and faster version of BERT.
The purpose of the project:
Recreate the original paper's approach
Train BERT on IMDB dataset
Added our contribution
Analyze both models
Prepare report in Google Colab
Submit code through GitHub

2.RESEARCH PAPER DETAILS
PAPER:- BERT:Pre-training of Deep Bidirectional Transformers
AUTHORS:- Jacob Devlin et al.
YEAR:-2019
GitHub SOURCE:- https://huggingface.co/transformers/

3. DATASET
DATSET:- IMDB Movie Reviews
SAMPLES:- 50,000
LABELS:- Positive/Negative
SOURCE:- https://huggingface.co/datasets/imdb
We chose this dataset because it is used in various in NLP classification models.

4. PROJECT STRUCTURE
📁 AIDI1002_Final_Project
│
├── 📄 Final_Project.ipynb # Main Colab notebook (report + code)
└── 📄 README.md # This file

5. MODELS IMPLEMENTED
a) BERT(Reproduction)
- Pretrained: bert-base-uncased
- Fine-tuned on IMDB
- Metrics calculated: Accuracy, F1 Score, Confusion matrix, Learning curves
b) DistilBERT(Contribution)
- Pretrained:distilbert-base-uncased
- Rapid, lighter transformer model
- Same training+evaluation pipeline
- Direct performance differentiation with BERT
This participation represent the balance between performance and efficiency.

6. HOW TO RUN THE CODE
OPTION 1- Google Colab
a) Open the .ipynb file in GitHub
b) Click "Open in Cloab"
c) Run all the cells top-to-bottom
d) No setup required-everything installs inside the notebook.
OPTION 2- Local Machine
Install required pacakges:
pip install transformers datasets toech scikit-learn matplotlib
Then run the notebook using:
jupyter notebook

7. CONTRIBUTION EXPLANATION
The contribution for this project:
a) Implementing DistilBERT
b) Training it on the same dataset
c) Analyzing performance with BERT

8. REFERENCES
a) Devliln, Jacob et al. "BERT:Pre-training of Deep Bidirectional Tramsformers for Language Understanding."NAACL,2019.
b) Hugging Face Transformers: https://huggingface.co/transformers/
c) IMDB Dataset: https://huggingface.co/datsets/imdb
d) DistilBERT Paper: Sanh et al.,2019


