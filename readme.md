
## Introduction
In this project, we propose a model that leverages a Convolutional Neural Network (CNN) to recommend fashion products similar to the user's input.
## Training the neural networks
Once the data is pre-processed, the neural networks are trained, utilizing transfer learning 
from ResNet50. More additional layers are added in the last layers that replace the architecture and 
weights from ResNet50 in order to fine-tune the network model to serve the current issue.

## Recommendation generation
To generate recommendations,our system recommends similar images using nearest neighbors and cosine similarity. It finds the 5 closest matches and shows their images.


### Dataset Link
The images from Kaggle Fashion Product Images Dataset.

Don't forget to add the images folder to the project folder from the dataset link after uploading it.

## Screenshots

## Installation

Use pip to install the requirements.

~~~bash
pip install -r requirements.txt
~~~

## Usage
To run the web server, simply execute streamlit with the main recommender app:

```bash
streamlit run main.py
```