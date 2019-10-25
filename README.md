# Streamlit Demo

Streamlit demo for classifying animals. You can use Streamlit to create interactive Data Science pages, deployable to the web through all major deployment surfaces. 

## Getting Started

Using a python3 (preferably 3.7) environment, run the following to install all the libraries used in this repository:
```
pip install -r requirements.txt
```
Recommend using conda or virtualenv to sandbox your work

### Manual Install 
Recommend using [Anaconda](https://www.anaconda.com/distribution/). Anaconda does not come with TensorFlow or Keras so you will need to install those seperately. 
```
pip install pandas numpy streamlit tensorflow keras
```
For additional information on installing TF & Keras: [TensorFlow](https://www.tensorflow.org/install), [Keras](https://keras.io/#installation)

For additional information on Streamlit: [Docs](https://streamlit.io/docs/)

### Training Models
You can either train your own model inside the Streamlit app or from the command line using training.py. Otherwise, an existing model.h5 and weights.h5 have been included for you. 
