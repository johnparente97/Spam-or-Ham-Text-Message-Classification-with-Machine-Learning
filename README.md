# Text-Message-Spam-Detector
This is a jupyter notebook created to examine incoming text messages and to detemine whether or not the message is spam. The data consisteed of over 5000 text messsages. The data sets were split to distinguish the spam and the ham (real message). 

A SVM is then built and trained on the data. The TFID vectorizers converts the text messages into TF-IDF features. Linear SVC learns to classify text based on these numerical features, finding a hyperplane that separates spam and ham messages efficiently. Together, TF-IDF and Linear SVC create an effective text classification system by transforming text into numerical representations and learning to classify it accurately.

Gradio is then deployed to interact with the text classification model in the jupyter notebook. Users can input text messages and get predictions for whether or not they're spam or ham.  

Resources:
Module 21 Challenge Files,
Github Copilot,
Chat GPT
