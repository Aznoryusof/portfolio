## Personal Projects

---

### Step-by-Step Guide on Fine-Tuning Llama 2 13B for Meeting Transcript Summarisation. 

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1qGiYBDwrnWagtpmpASsjvwg5zRUau9B8?usp=sharing)

In the notebook linked above, I demonstrate how to conduct instruction-tuning on Meta's open-sourced Llama 2 13B base model to achieve scores that are close to the State-of-the-Art on summarising meeting transcriptions.

The model was fine-tuned on the MeetingBank Dataset using the QLoRa technique from the PEFT library and took ~7 hours to train on an A100 GPU on Google Colab.

The fine-tuned model can be accessed from my Hugging Face Repository linked below for futher fine-tuning (on a small dataset) in order to achieve any style of summary (e.g. format, tone, lexicon etc.) 

<img src="images/llama2_image.png?raw=true" alt=""/>

[Dataset](https://arxiv.org/abs/2211.04367) &#124; [Paper](https://github.com/Aznoryusof/portfolio) &#124; [Hugging Face Repository](https://github.com/Aznoryusof/portfolio)

---

### Gendered Names: Finding Patterns in Names with Character-Level Bi-LSTMs for Gender Prediction Task

[![Run in Google Colab](https://img.shields.io/badge/Colab-Run_in_Google_Colab-blue?logo=Google&logoColor=FDBA18)](https://colab.research.google.com/drive/1qGiYBDwrnWagtpmpASsjvwg5zRUau9B8?usp=sharing)

In this challenge, I built a character-level Bi-directional LSTM with a feed-forward neural network and fine-tuned its hyper-parameters to predict the gender of names with an accuracy of 91.5% on the test set.

The full code and analysis is linked in the Google Colab Notebook.

<img src="images/names_project.png?raw=true" alt=""/>

[Dataset](https://drive.google.com/file/d/1psEq5Sp_8_ILfgsO4DgcLLzs5ykU3Wg0/view?usp=sharing)

---

