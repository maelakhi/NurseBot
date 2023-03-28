# NurseBot
This project is built to create a Deep Learning conversational chatbot that provides mental health support by preventing suicide, depression, and reducing stress. This project
will be designed by a contextual chatbot framework allowing the user to have a conversation with the chatbot and treated the user with psychological treatment.

## Objective
There are several objectives that may include better aim which are:
1. To demonstrate the use of a contextual system with the implementation of the Deep
Learning model.
2. To provide mental health support in solving mental health issues by creating an
interactive chatbot system that can serve as a virtual friend/therapist.
3. To create a system that can detect any signs of depression, stress, or any mental
health illness.


## System Architecture
![image](https://user-images.githubusercontent.com/128575214/228232820-7cced6ce-0856-4f64-8ff3-a7a9ca9a3d45.png)

The architecture of NurseBot consist of the user, NurseBot, the deep learning model, NLP, and
predefined questions, intents & responses. Some of the parts of the system are being simplified in
order to properly illustrate the NurseBot system architecture without explaining the whole details
of each part of the system such as NLP with its tasks on lemmatization, tokenization, as well as
bag of words.
The system will expect the input from the user to the NurseBot system using the GUI provided by
using Tkinter library in the program. After that, NurseBot will receive the input from the user and
then the system will classify the intent and trying to predict based on the input given to the user
using the deep learning model. The model will classify the intent based on the dataset that consist
of predefined questions, intents, and the correct responses. Moreover, the intent that is being
classified based on the prediction of the deep learning model will return a correct response
according to the tag and intent in the dataset to the NurseBot so that the system will answer the
user properly and accurately.
