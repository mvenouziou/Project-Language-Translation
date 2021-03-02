# Neural Translation Model

*Capstone Project for Imperial College London's "Customising your models with TensorFlow 2" course on Coursera.*

The following program is my a translation model to convert English sentences into German. It consists of an RNN encoders and decoders.

Credits:

- This was a course capstone project, where the necessary steps were outlined by the course instructor. RNN diagrams and a small number of functions were provided by the instructor, and are noted as such within their function descriptions. Otherwise, this is my own work based on techniques taught in the course.

- Course info: www.coursera.org/account/accomplishments/verify/3X7RJ4S9ZLEK.

- The dataset consists of English/German sentence pairs from the Tatoeba Project. *(www.manythings.org/anki)

- The encoder utilizes pretrained embeddings from Tensorflow Hub, https://tfhub.dev/google/nnlm-en-dim128/1. They cite Yoshua Bengio, Réjean Ducharme, Pascal Vincent and Christian Jauvin's paper, A Neural Probabilistic Language Model. Journal of Machine Learning Research, 3:1137-1155, 2003.
