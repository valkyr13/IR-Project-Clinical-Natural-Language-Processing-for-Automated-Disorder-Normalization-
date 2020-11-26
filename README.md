# IR-Project-Clinical-Natural-Language-Processing-for-Automated-Disorder-Normalization-
Team 12: Alisa P (171IT207) , Vandana S (171IT246) , Sreeja (171IT114)

Model run using Goggle Collaboratory.

Dataset:  https://www.kaggle.com/rsnayak/hackathon-disease-extraction-saving-lives-with-ai?select=train_3PIRKSI

Sci spacy pre-trained model is used for ner but it doesnt give better results.(f1_score=0.521)
So we train the model with data which is grouped by doc_id because we want our model to predict on document level.

<img src="images/training_data.png" width="500">

Test data is shown in figure below.

<img src="images/test_data.png" width="500">
