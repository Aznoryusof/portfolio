## Personal Projects

---

### Gendered Names: Finding Patterns in Names with Character-Level Bi-LSTMs for Gender Prediction Task

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1qGiYBDwrnWagtpmpASsjvwg5zRUau9B8?usp=sharing)

In this challenge, I built a character-level Bi-directional LSTM with a feed-forward neural network and fine-tuned its hyper-parameters to predict the gender of names with an accuracy of 91.5% on the test set.

The full code and analysis is linked in the Google Colab Notebook.

<img src="images/names_project.png?raw=true" alt=""/>

[Dataset](https://drive.google.com/file/d/1psEq5Sp_8_ILfgsO4DgcLLzs5ykU3Wg0/view?usp=sharing)

---

### Best Practices for Detecting Fraudulent Transactions using Machine Learning

[![View on GitHub](https://img.shields.io/badge/GitHub-View_on_GitHub-blue?logo=GitHub)](https://github.com/Aznoryusof/learn_fraud_detection/blob/master/notebook/Fraud%20Detection%20Predictive%20Model.ipynb)

This is a playbook for experimenting with a variety of Machine Learning Models to detect low occuring events - in this case, credit card fraud. 

<img src="images/fraud_detection_system.png?raw=true" alt=""/>

[Dataset](https://www.kaggle.com/datasets/dermisfit/fraud-transactions-dataset?resource=download) &#124; [Github](https://github.com/Aznoryusof/learn_fraud_detection/tree/master)

---

### Step-by-Step Guide on Fine-Tuning Llama 2 13B for Meeting Transcript Summarisation (Ongoing). 

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1MWTMqxInT62N6d0BYPmQULhIDlkJm2m-?usp=sharing)

In the notebook linked above, I demonstrate how to conduct instruction-tuning on Meta's open-sourced Llama 2 13B base model.

The model was fine-tuned on the MeetingBank Dataset using the QLoRa technique from the PEFT library and took ~7 hours to train on an A100 GPU on Google Colab.

More work will be done to evaluate the performance of the model.

<img src="images/llama2_image.png?raw=true" alt=""/>

[Dataset](https://huggingface.co/datasets/Aznor/MeetingBank-original) &#124; [Paper](https://aclanthology.org/2023.acl-long.906.pdf)