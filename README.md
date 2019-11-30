# Neural Networks for Data Science Applications (2019/2020)
## Notebooks and lab sessions

This is a repository for the lab sessions of the following course:
http://ispac.diet.uniroma1.it/scardapane/neural-networks-for-data-science-applications/

The course uses TensorFlow 2.0, moving from its core library of linear algebra up to the use of complex layers for image and audio applications.

### Lab session 1 - TensorFlow 2.0 basics & Automatic differentiation

It describes the linear algebra core of TensorFlow 2.0, before moving on to automatic differentiation with tf.GradientTape and a simple example of gradient descent.

[[See online on nbviewer]](https://nbviewer.jupyter.org/github/sscardapane/neural-networks-for-data-science/blob/master/Notebook_1_Basics_and_automatic_differentiation.ipynb) - [[Direct download]](https://github.com/sscardapane/neural-networks-for-data-science/blob/master/Notebook_1_Basics_and_automatic_differentiation.ipynb)

### Lab session 2 - Linear models for regression and classification

We use the low-level API of TensorFlow to implement a simple linear regression algorithm. Then, we extend the example to binary classification by substituting some of our previously-defined functions with the tf.keras equivalents.

[[See online on nbviewer]](https://nbviewer.jupyter.org/github/sscardapane/neural-networks-for-data-science/blob/master/Notebook_2_Linear_models.ipynb) - [[Direct download]](https://github.com/sscardapane/neural-networks-for-data-science/blob/master/Notebook_2_Linear_models.ipynb)

### Lab session 3 - Feedforward neural networks with tf.data and tf.layers

We build a feedforward neural network, this time on a realistic binary classification problem (prediction of super-symmetric particles from simulated measurements of a particle collider). We consider the use of tf.data to iterate on the dataset, and tf.keras.layers to actually build the model.

[[See online on nbviewer]](https://nbviewer.jupyter.org/github/sscardapane/neural-networks-for-data-science/blob/master/Notebook_3_Feedforward_neural_networks.ipynb) - [[Direct download]](https://github.com/sscardapane/neural-networks-for-data-science/blob/master/Notebook_3_Feedforward_neural_networks.ipynb)

### Lab session 4 - Building convolutional neural networks

We train a VGG convolutional neural network on a dataset released for the [In Codice Ratio](http://www.inf.uniroma3.it/db/icr/) (ICR) project. The dataset considers optical character recognition on Latin handwritten characters, segmented from a portion of the Vatican Secret Archives. We introduce tf.layers, keras.Model, and the ImageDataGenerator, along with callbacks and the TensorBoard.

[[See online on nbviewer]](https://nbviewer.jupyter.org/github/sscardapane/neural-networks-for-data-science/blob/master/Notebook_4_Building_convolutional_neural_networks.ipynb) - [[Direct download]](https://github.com/sscardapane/neural-networks-for-data-science/blob/master/Notebook_4_Building_convolutional_neural_networks.ipynb)

### Lab session 5 - Advanced convolutional networks

We build from scratch multiple CNNs (including among their layers batch normalization, dropout, and residual connections), with regularization and a custom initialization function, on a toy autonomous driving task. We show how to create a flexible image pipeline with tf.data, and how to improve code efficiency with tf.function.

[[See online on nbviewer]](https://nbviewer.jupyter.org/github/sscardapane/neural-networks-for-data-science/blob/master/Notebook_5_CNNs_from_scratch.ipynb) - [[Direct download]](https://github.com/sscardapane/neural-networks-for-data-science/blob/master/Notebook_5_CNNs_from_scratch.ipynb)

### Lab session 6 - Text classification with neural network

We build several text classification models on the IMDB reviews dataset: (i) a linear classifier with pre-trained embeddings; (ii) a linear classifier with learned word embeddings and manual tokenization; (iii) a convolutional neural network with learned embeddings. We also introduce TensorFlow Datasets and TensorFlow Hub.

[[See online on nbviewer]](https://nbviewer.jupyter.org/github/sscardapane/neural-networks-for-data-science/blob/master/Notebook_6_Text_classification_with_neural_networks.ipynb) - [[Direct download]](https://github.com/sscardapane/neural-networks-for-data-science/blob/master/Notebook_6_Text_classification_with_neural_networks.ipynb)

### Lab session (extra) - Recurrent neural networks

A series of examples on how to use recurrent neural networks: first by counting symbols, then by building a more elaborate encoder/decoder architecture for sorting. We also introduce a series of important layers (Masking, TimeDistributed), and the padded batch from the tf.data.Dataset object.

[[See online on nbviewer]](https://nbviewer.jupyter.org/github/sscardapane/neural-networks-for-data-science/blob/master/Notebook_extra_Recurrent_neural_networks.ipynb) - [[Direct download]](https://github.com/sscardapane/neural-networks-for-data-science/blob/master/Notebook_extra_Recurrent_neural_networks.ipynb)
