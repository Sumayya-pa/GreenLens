# GreenLens

The main objective of this project is to familiarize with machine learning and subsequently apply the knowledge gained in solving a real-world problem. We choose the project    topic chakka-manga classifier. As the name indicates we have to classify jackfruits and mangoes from a given sets of data using machine learning.We work in a team of three. At starting we don't have much knowledge,so we started to watch youtube videos and start coding parallely.We built a CNN in keras using Python.The web app can classify given mangoes and jackfruits.

## Team Members
1.Diya Fathima [https://github.com/DiaFathima ]

2.Sumayya P A  [https://github.com/Sumayya-pa ]

3.Husna Fathima U M [https://github.com/husna-fathima25]

## Team ID
BFH/rec3S0yXm3CcoZQp9/2021

## Link to product walkthrough
https://www.loom.com/share/512bbdc09dea4217ae4bb70ab3ee6bcc

## How It Works?
1.A CNN algorithm is created using tensorflow and keras libraries.

2.The training and testing datasets are created using the images of mango and jackfruit from Kaggle dataset.

3.A trained model created using the dataset is saved as '.h5' file format.

4.A web app is created using Gradio.

5.The trained model is loaded in the web app backend.

6.User can upload one image at a time to the web app, it is then saved into the folder named 'image'.

7.Image is processed in the trained ML model and it will return the prediction as output whether the image is jackfruit or mango.

# Libraries Used
1.numpy

2.pandas

3.matplotlib

4.keras

5.tensorflow

6.matplotlib.pyplot

## How To Configure
![image](https://user-images.githubusercontent.com/84271557/119643322-3960f180-be39-11eb-8887-01242c8e4354.png)

## How To Run
1.install the gradio using pip install and iport the libraries.

2.Define the function and the function characteristics.

3.Define input as image and the for output, it is defined to print the probability of the uploaded image in the 2 classes.

4.When it starts to run, the local URL will load in the terminal which will work for 24 hrs only. And there will be a copy in the terminal itself for the prediction.

5.Open the URL in the browser and upload the image to be predicted
