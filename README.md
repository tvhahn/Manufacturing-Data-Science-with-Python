# Manufacturing-Data-Science-with-Python

Data science and machine learning applied to problems in manufacturing.

## Contents

#### [Metal Machining](https://github.com/tvhahn/Manufacturing-Data-Science-with-Python/tree/master/Metal%20Machining)


Anomaly detection as applied to metal machining using the UC Berkely milling data set.  The data set can be downloaded from the the [NASA Prognostics Center of Excellence website](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/).

- [1.A_milling-data-exploration.ipynb](https://github.com/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.A_milling-data-exploration.ipynb)  [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.A_milling-data-exploration.ipynb) Notebook explores the milling data set. You'll get familiar with the data set and visualize the cutting signals. My [blog post](https://www.tvhahn.com/posts/milling/) explains the notebook in detail, and you can run the notebook [here](https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.A_milling-data-exploration.ipynb).
<p align="center">
  <img alt="face milling" src="./Metal Machining/images/face_milling.svg" width="150px">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="flank wear" src="./Metal Machining/images/flank_wear.svg" width="200px">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="cut signals" src="./Metal Machining/images/cut_signals.png" width="100px">
&nbsp; &nbsp; &nbsp; &nbsp;
</p>


- [1.B_building-vae.ipynb](https://github.com/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.B_building-vae.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.B_building-vae.ipynb) Notebook lays out the construction and training of a variational autoencoder (VAE) using the milling data. Here's the [blog post](https://www.tvhahn.com/posts/building-vae/) explaining the notebook, and you can run the notebook [here](https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.A_milling-data-exploration.ipynb). 

<p align="center">
  <img alt="vae" src="./Metal Machining/images/vae.svg" width="200px">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="model architecture" src="./Metal Machining/images/model_architecture.svg" width="200px">
&nbsp; &nbsp; &nbsp; &nbsp;
  <img alt="random search" src="./Metal Machining/images/vae_training_random_search.png" width="200px">
</p>

- [1.C_anomaly-results.ipynb](https://github.com/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.C_anomaly-results.ipynb) [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.C_anomaly-results.ipynb)


