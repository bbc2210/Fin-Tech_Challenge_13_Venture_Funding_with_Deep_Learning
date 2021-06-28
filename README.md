# Fin-Tech_Challenge_13_Venture_Funding_with_Deep_Learning

You work as a risk management associate at Alphabet Soup, a venture capital firm. Alphabet Soup’s business team receives many funding applications from startups every day. This team has asked you to help them create a model that predicts whether applicants will be successful if funded by Alphabet Soup.

The business team has given you a CSV containing more than 34,000 organizations that have received funding from Alphabet Soup over the years. With your knowledge of machine learning and neural networks, you decide to use the features in the provided dataset to create a binary classifier model that will predict whether an applicant will become a successful business. The CSV file contains a variety of information about these businesses, including whether or not they ultimately became successful.



## Technologies

This project leverages python 3.7 with the following packages:

* [TensorFlow 2.0](https://www.tensorflow.org/) - TensorFlow is an end-to-end open-source platform for machine learning. It allows us to run our code across multiple platforms in a highly efficient way.
* [Keras](https://keras.io/about/) - Keras is an abstraction layer on top of TensorFlow that makes it easier to build models.



## Installation Guide

Before running the application first install the following dependencies.

**Note**: If you're using an Apple computer with an M1 Chip, you will **NOT** install these tools. The Apple M1 Chip is not currently compatible with a typical Tensorflow installation. Use [Google Colab](https://colab.research.google.com/) instead.

```python
# Install TensorFlow
pip install --upgrade tensorflow

# TensorFlow install is complete, and Keras is included with TensorFlow 2.0. Run the following command to verify that the package is available
python -c "import tensorflow as tf;print(tf.__version__)"

```



## Usage

To use the Crypto Arbitrage application simply clone the repository, download applicants_data.csv,   and run the **venture_funding_with_deep_learning.ipynb** with:

```python
jupyter lab
```

