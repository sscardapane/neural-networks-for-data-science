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

We train a VGG convolutional neural network on a dataset released for the [In Codice Ratio](http://www.inf.uniroma3.it/db/icr/) (ICR) project. The dataset considers optical character recognition on Latin handwritten characters, segmeneted from a portion of the Vatican Secret Archives. We introduce tf.layers, keras.Model, and the ImageDataGenerator, along with callbacks and the TensorBoard.

[[See online on nbviewer]](https://nbviewer.jupyter.org/github/sscardapane/neural-networks-for-data-science/blob/master/Notebook_4_Building_convolutional_neural_networks.ipynb) - [[Direct download]](https://github.com/sscardapane/neural-networks-for-data-science/blob/master/Notebook_4_Building_convolutional_neural_networks.ipynb)
