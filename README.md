# swahili-speech-text
# Introduction
Speech recognition technology allows for hands-free control of smartphones, speakers, and even vehicles in a wide variety of languages. Companies have moved towards the goal of enabling machines to understand and respond to more and more of our verbalized commands. Therefore, my task in this project is to build a deep learning model that is able to convert Swahili speech to text. As required by World Food Program, the system will be in an intelligent form that collects nutritional information of food bought and sold at markets in two different countries in Africa - Ethiopia and Kenya.
# Data
The swahili data is available here: https://github.com/getalp/ALFFA_PUBLIC. It has two folders; train and test dataset folders, that was both audios and the their respective transcriptions.
# Data cleaning
Data cleaning is a crucial step in building any machine learning model. In this project, all the punctuations were removed since they add no value to the model.
# Data Preprocessing
No model can take in the raw speech, therefore the data was processed to have MFCC that give important features required by the model.
# Modelling
Acoustic model helped in associating the sound to their respective characters. RNN approach proved to be the most effective method in deep learning for converting speech to text.
# Evaluation
In evaluating the model, the Word Error Rate was the most effective way to determine the error.
