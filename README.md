# transfer-learning-metoo

In this repository, we present our approach and codes for the BigMM Grand Challenge 2020. The contest focuses on building Multimodal classification model on tweets relevant to #MeToo Movement. The tweets comprise of multiple annotated linguistic aspects, like Stance, Relevance, Presence of Hate Speech, Sarcasm, Justification aspects etc.

Our best performing approach ranked **first** (among 38 submissions) in the leader-board.
 
- 01-Preproc_baseline.ipynb -> Code for  Data Preprocessing and EDA
- 02-Preproc_Tree.ipynb -> Code for Tree and Ensemble methods
- 03-Embedding_BiLSTM.ipynb -> Code for Glove Embeddings and BiLSTM
- 04-BERT_Classification.ipynb -> Code for BERT and Minority Class Oversampling
- 05-ULMFiT_Stance.ipynb  -> Code for our ULMFiT Model, load vocabulary from `model/` and language model from [here](https://drive.google.com/file/d/1fILUAFhjxUe6ass4olak226bxonrQs9F/view?usp=sharing).


-----------

- Challenge Link : https://sites.google.com/iiitd.ac.in/bigmm2020datachallenge/home 
- Competition Platform and Leaderboard : https://www.kaggle.com/c/ieee-bigmm-data-challenge/overviewv

------------

- System Description [paper](https://github.com/vntkumar8/transfer-learning-metoo/raw/master/doc/metoo-bigmm.pdf) describing the methodology *to  appear at* IEEE Multimedia Big Data
