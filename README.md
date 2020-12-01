# PoetBot
A chatbot that can give you poems that matches with your feelings.

Files:
1. BERT_Emotion_Classifier:
   A Text Emotion Classifier trained with Kaggle's "Emotions dataset for NLP"(https://www.kaggle.com/praveengovi/emotions-dataset-for-nlp)
   Modified from the notebook provided by Praveen (https://www.kaggle.com/praveengovi/classify-emotions-in-text-with-bert)
2. Classify_Poems:
   We take the first 1,000 poems from kaggle's "Complete poetryfoundation.org dataset" ("https://www.kaggle.com/johnhallman/complete-poetryfoundationorg-dataset") and classified them into the 6 emotion categories and save them as csv. Note that some of the poems are discarded if the certainty of the prediction is not high enough.
3. 
