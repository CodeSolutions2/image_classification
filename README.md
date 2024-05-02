# test_4_webapps

Purpose: The purpose of this Tensorflow.js Webapp is to demonstrate usage of the Tensorflow.js MobileNet API in Javascript/HTML, and to demonstrate prediction of a custom model that predicts similar types of obejcts (ie: apples from tomatoes). In this example, the MobileNet API can not predict apples from tomatoes well, without finetuning. Finetuning of the MobileNet model is demonstrated at https://www.kaggle.com/code/jamilahfoucher/tensorflowjs-image-classification-model-deploy. Additionally, training a MPCNN model with edge detection pre-processing showed similar accuracy as the finetunned MobileNet model, at accuracy of 0.9. The MPCNN model with edge detection pre-processing is available at Kaggle Models (https://www.kaggle.com/models/jamilahfoucher/image_classification_via_edge_detection).

The Tensorflow.js Webapp is located at : https://CodeSolutions2.github.io/test_4_webapps/index.html .

## Upwork
The objective of this work was to create a web application that can automatically label images that are in a GitHub repository. The user inputs the Github repository url and the web application outputs a table/csv file of each repo image with a label. This application is useful for creating supervised image prediction models, because it is necessary to have a reliable label for each image that a supervised model will be trained on. 

There are three tiers of this workflow: Webapp code-Tensorflow models, Webapp code-Custom model, Webapp code-Custom BigData. These code workflows/solutions will be delivered with instructions on how to use the code.
Tier 1: read images from a GitHub repo, use a pre-trained Tensorflow.js model (mobilenet or ssdcoco) to detect objects in each image, create a table of the image name and predicted label.  
Tier 2: perform tier 1 functionality and train a Custom trained Tensorflow model specifically for the data.
Tier 3:  perform tier 2 functionality and  efficient memory usage strategies, such as batching reading and writing data to Cloud Storage, to accommodate large quantities of data (Big Data).

[Available for purchase on Upwork](https://www.upwork.com/services/product/development-it-image-labeling-webapp-using-tensorflow-js-1752011396357709824)

## Extra

If you are interested in making your own GitHub Web Page, the steps to transform a GitHub Repository are below:

0. Configure GitHub Pages: Go to your repository on GitHub. Click on the "Settings" tab, scroll down to the "GitHub Pages" section. Under the "Source" dropdown, select "master branch" or the branch you want to use for deployment. Click on the "Save" button.

1. Access your deployed website: After the configuration step, you will see a message indicating the URL where your website is deployed. It usually follows the pattern `https://<your-github-username>.github.io/<repository-name>`.
  
It may take a few minutes for your changes to be reflected on the deployed website. Good luck and thanks for the interest!
