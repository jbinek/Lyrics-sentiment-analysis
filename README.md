# Transformers network for emotion analysis of songs' lyrics

The main objective of the project was to apply a selected technique or mechanism in a deep learning approach to solve a selected task. The topic we chose concerned song lyrics, specifically the use of transformers network for emotion analysis of songs' lyrics. The choice of such a topic and task was motivated by the fact that the use of transformers and the technologies related to NLP in general has become very popular. Latest developments in NLP algorithms such as [token-free models](https://ruder.io/ml-highlights-2021/index.html#12tokenfreemodels) indicate their dynamic development and make them a good investment for the future. 

A dataset containing 2751 song lyrics was used to complete the project. The lyrics were annotated using Valence and Arousal values of the words (based on Russell's model) in one of the 4 quadrants/categories:

- Q1 - Happy   (high Valence and high Arousal)
- Q2 - Angry   (low Valence and high Arousal)
- Q3 - Sad     (low Valence and low Arousal)
- Q4 - Relaxed (high Valence and low Arousal)

Fine tuning an already existing transformers network was done so that for a given lyrics it returns the emotion it brings. The auto-regressive language XLNet model was used to perform the multilabel text classification task.

(more detailed descritpion in dnn_report.pdf file)

