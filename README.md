# image_classification

## Tensorflow.js MobileNet compared with a custom model (MPCNN model) with edge detection pre-processing

A web application that classifies two similar images like an apple and a tomato using fundamental edge detection methods. The purpose of this Tensorflow.js Webapp is to demonstrate usage of the Tensorflow.js MobileNet API in Javascript/HTML, and to demonstrate prediction of a custom model that predicts similar types of obejcts (ie: apples from tomatoes). In this example, the MobileNet API can not predict apples from tomatoes well, without finetuning. However, a custom model using a Max Pooling Convolutional Neural Network (MPCNN) structure with edge detection pre-processing can predict apples from tomatoes with similar accuracy as the finetunned MobileNet model (an accuracy of 0.9).

[Version 0 - non-functional due to function updates] https://CodeSolutions2.github.io/image_classification/index.html

[Version 1 - In progress] https://CodeSolutions2.github.io/image_classification/index.html


## Kaggle
- Finetuning of the Tensorflow MobileNet model - https://www.kaggle.com/code/jamilahfoucher/tensorflowjs-image-classification-model-deploy
- The MPCNN model with edge detection pre-processing is available at Kaggle Models - https://www.kaggle.com/models/jamilahfoucher/image_classification_via_edge_detection


## Upwork
The objective of this work was to create a web application that can automatically label images that are in a GitHub repository. The user inputs the Github repository url and the web application outputs a table/csv file of each repo image with a label. This application is useful for creating supervised image prediction models, because it is necessary to have a reliable label for each image that a supervised model will be trained on. 

There are three tiers of this workflow: Webapp code-Tensorflow models, Webapp code-Custom model, Webapp code-Custom BigData. These code workflows/solutions will be delivered with instructions on how to use the code.
Tier 1: read images from a GitHub repo, use a pre-trained Tensorflow.js model (mobilenet or ssdcoco) to detect objects in each image, create a table of the image name and predicted label.  
Tier 2: perform tier 1 functionality and train a Custom trained Tensorflow model specifically for the data.
Tier 3:  perform tier 2 functionality and  efficient memory usage strategies, such as batching reading and writing data to Cloud Storage, to accommodate large quantities of data (Big Data).

[Available for purchase on Upwork](https://www.upwork.com/services/product/development-it-image-labeling-webapp-using-tensorflow-js-1752011396357709824)

