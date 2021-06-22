# Inside a NLP multitasking neural network. BERT, one model to rule them all
NLP is an well known topic inside AI field. A wide range of applications are collected into this area, from text classification as sentiment analysis to text generation like translation. With the potential technological growth, these tools play a critical role in daily business automating certain tasks. In spite of its benefit, NLP has been a leveraged field into AI during many years. Training times of RNNs and the difficulty to capture long-term dependencies were an extended problem. However, the emergence of the transformer architecture with its pure attention mechanisms represented a critical change in the development of models. This results in the publication of BERT, overcoming all current models and getting state-of-the-art results. This model was pre-trained and it is defined for how easy and fast can be fine-tuned for most NLP tasks. In order to show this process, two applications are developed for sentiment analysis and question answering problems. In both cases, training time was really short compared with an RNN, obtaining an outstanding performance in test set. BERT implied the origin of pre-training language models, which currently is the dominant trend in NLP area. In addition, it resulted in the solution for long training times and a huge amount of data in order to have a reliable model for a specific task.

## Notebook
The implementation has been carried out in a notebook with the option to run it from Colab. The file is: 
**Inside a NLP multitasking neural network. BERT, one model to rule them all.ipynb**

## Implemented Models
Two BERT models are implemented to solve _Sentiment Analysis_ and _Question Answering_ tasks. Their parameters as well as the training arguments are stored in their respective folders in order to be able to load them. Used tokenizers are also saved. Everything is in **models** folder.

## Results
Obtained results respect both models are stored in **results** folder. They reflect training and test statistics.

## Memory
This work is the topic of my Bachelor Thesis. For this reason, the memory is also published with more information and details in case it is useful to check it. The file is: **20210624_tfg_Ion_Bueno.pdf**

## Cite
Thanks for reading! If you find it useful, feel free to use it. You can cite it as:
```
@mastersthesis{opennmt,
  author    = {Ion Bueno},
  title     = {Inside a NLP multitasking neural network. BERT, one model to rule them all},
  school    = {University Carlos III of Madrid},
  year      = {2021},
  month     = {jun},
  address   = {Madrid, Spain},
  url       = {https://github.com/ion-bueno/bert-from-inside}
}
```
