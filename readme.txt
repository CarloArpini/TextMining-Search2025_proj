

REQUIREMENTS: 

-Download of https://huggingface.co/stanfordnlp/glove/resolve/main/glove.twitter.27B.zip for GloVe Embeddings

-Download of Twitter Dataset from https://ieeexplore.ieee.org/document/9378065. A convenient link is https://www.kaggle.com/datasets/andrewmvd/cyberbullying-classification.

-Download of file "Words.txt" from https://github.com/dwyl/english-words?tab=readme-ov-file 

recommended: 32GB RAM.

USAGE: 

Start by following the notebook "Preprocessing.ipynb", which will clean the dataset and output the file "cleantweets.csv". 

Once that is done, you can follow up with any of the other ipynb files; the recommended path is to start with BoW.ipynb, then GloVe.ipynb, then sBERT.ipynb - saving the best for last ;)