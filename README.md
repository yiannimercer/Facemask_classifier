# Facemask Classifier
Basic Facemask Image Classifier

## Overview

For this project, I built a Facemask image classifier to recognize when indviduals are wearing facemasks.  This can be useful for stores and other establishments when customers are entering the establishment.  A camera can be placed at the front of the business' entrance and can monitor individuals coming into the store and alert employees when individuals enter without a face mask.  This is the underlying model that can be utilized for building the application that can be capable of the formerly mentioend features. 

I was able to get the model to predict nearly 98% accuracy after extensive amount of data cleaning. I used transfer learning on a Convalutional Neural Network trained on resnet34.

## Data Collection

I used the facemasks dataset provided here: 
https://github.com/prajnasb/observations/tree/master/experiements/data

## Config
 
I recommend using Google Colab for this project as it makes the GPU configuration far easier.  
