# Inside a NLP multitasking neural network. BERT, one model to rule them all
NLP is a well known topic inside AI field. A wide range of applications are collected into this area, from text classification as sentiment analysis to text generation like translation. With the potential technological growth, these tools play a critical role in daily business automating certain tasks. In spite of its benefit, NLP has been a leveraged field into AI during many years. Training times of RNNs and the difficulty to capture long-term dependencies were an extended problem. However, the emergence of the transformer with its pure attention mechanism represented a critical change in the area. This results in the publication of BERT, overcoming all current models and getting state-of-the-art results. This model was pre-trained and it is defined for how easy and fast can be fine-tuned for most NLP tasks. In order to show this process, two applications are developed for sentiment analysis and question answering problems. In both cases, training time was really short compared with a RNN, obtaining an outstanding performance in test set. BERT boosted pre-training language models, which currently is the dominant trend in NLP area. In addition, it resulted in the solution for long training times and processing a huge amount of data in order to have a reliable model in a specific task.

## Notebook
The implementation has been carried out in a notebook with the option to run it from Colab. The file is: 
**Inside a NLP multitasking neural network. BERT, one model to rule them all.ipynb**. Used images are loaded from **images** folder.

## Implemented Models
Two BERT models are implemented to solve _Sentiment Analysis_ and _Question Answering_ tasks. Their parameters and training arguments are stored in their respective folders to be able to load them for future use. Used tokenizers are also saved as well as training and test statistics. Everything is into **models** folder.

## Results
Obtained results respect both models are stored in **results** folder. There are examples of the final applications, predictions and results respect training and test.

## Memory and Presentation
This work is the topic of my Bachelor Thesis. For this reason, the memory is also published with more information and details in case it could be useful to check it. The file is: **memory.pdf**.

It is also available a short presentation about the project. The file is: **presentation.pdf**.

## Cite
Thanks for reading! If you find it useful, feel free to use it. You can cite it as:
```
@mastersthesis{bueno2021bert,
  author    = {Bueno, Ion},
  title     = {Inside a NLP multitasking neural network. BERT, one model to rule them all},
  school    = {University Carlos III of Madrid},
  year      = {2021},
  month     = {jun},
  address   = {Madrid, Spain},
  url       = {https://github.com/ion-bueno/bert-from-inside}
}
```
