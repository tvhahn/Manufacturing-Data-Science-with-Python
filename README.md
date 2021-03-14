# Manufacturing-Data-Science-with-Python
Data science and machine learning applied to problems in manufacturing.

## Contents

#### [Metal Machining](https://github.com/tvhahn/Manufacturing-Data-Science-with-Python/tree/master/Metal%20Machining)

Anomaly detection as applied to metal machining using the UC Berkely milling data set.  The data set can be downloaded from the the [NASA Prognostics Center of Excellence website](https://ti.arc.nasa.gov/tech/dash/groups/pcoe/prognostic-data-repository/).

- [1.A_milling-data-exploration.ipynb](https://github.com/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.A_milling-data-exploration.ipynb) explores the milling data set. You'll get familiar with the data set and visualize the cutting signals. My [blog post](https://www.tvhahn.com/posts/milling/) explains the notebook in detail, and you can run the notebook [here]((https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.A_milling-data-exploration.ipynb)). [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.A_milling-data-exploration.ipynb)



<div style="text-align: center; ">
<figure>
  <img src="./Metal Machining/images/vae.svg" alt="variational autoencoder process" style="background:none; border:none; box-shadow:none; text-align:center" width="400px"/>
  <div style="text-align: left; ">
  <figcaption style="color:grey; font-size:smaller">A variational autoencoder architecture (top), and an example of a data sample going through the VAE (bottom). Data is compressed in the encoder to create mean and standard deviation codings. The coding is then created, with the addition of Gaussian noise, from the mean and standard deviation codings. The decoder uses the codings (or latent variables) to reconstruct the input. (Image from author, based on graphic from Aurélien Geron)</figcaption>
  </div>
</figure>
</div>





- [1.B_building-vae.ipynb](https://github.com/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.B_building-vae.ipynb) lays out the construction and training of a variational autoencoder (VAE) using the milling data. Here's the [blog post](https://www.tvhahn.com/posts/building-vae/) explaining the notebook, and you can run the notebook [here](https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.A_milling-data-exploration.ipynb). [![Open In Colab](https://colab.research.google.com/assets/colab-badge.svg)](https://colab.research.google.com/github/tvhahn/Manufacturing-Data-Science-with-Python/blob/master/Metal%20Machining/1.B_building-vae.ipynb)

