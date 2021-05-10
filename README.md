# NLP-Shared-Task
Repository containing the files which where used to perform Native Language Identifation (L1) and Language Proficiency levels. These models were made as part of the Shared Task organized during the Natural Language Processing course at the University of Antwerp as part of the Master's in Digital Text Analysis

TABLE OF CONTENTS:
0 - Data-Stats
    A short overview exploring the specifics of the used data

1 - Model Selection
    In this notebook we explore several classifier machine learning models in order to select the       most suited for the task. In 1.1. we dive deeper into testing various combination of Support       Vector Machine Models
    
2. Feature selection
   We extract several features like character, word and POS n-grams as well as several other          syntactic features. In 2.1 we extract the same features from the test set as well
   
3. Experimentation
   We test the performance on both tasks while performing Gridsearch optimization. In 3.3 we          experiment with leaving out several features depending on each task in order to opimize            accuracy
   
4. Final model
   The final model gets trained and evaluated after which we perform our final predictions on the      test set.
   
   DeepLearning.ipynb
   An experiment with the dataset on the BERT model which did not result in any valid usage. Not      integrated in the final model.
   
   
   This repository also contains two Powerpoint Presentations which were used for presenting the      described experiment as part of the Natural Language Processing evaluation module during the      Master Digital Text Analysis at the University of Antwerp. (DePaepe_NLP_Task_report.pptx &        DePaepe_Pitch.pptx)
   
   
   
   
   


