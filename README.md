# Rock-Paper-Scissor Image Classifier Web App

**The web app for this rock-paper-scissor classifier: https://scenic-saguaro-82569.herokuapp.com/**

This is a simple image classification web app to predict whether an image of a hand formed a shape of rock, paper, or scissor.

The model for the web app was trained with the [rps dataset from Laurence Moroney](http://www.laurencemoroney.com/rock-paper-scissors-dataset/). This is a synthetic dataset of computer generated human hands with different colors that formed either rock, paper, or scissor. 

<p align="center">
  <img width="700" height="500" src=https://github.com/marcellusruben/rock_paper_scissor_web_app/blob/master/hand_sign.png>
</p>

Below is the screenshot of the simple web app:

<p align="center">
  <img width="300" height="500" src=https://github.com/marcellusruben/rock_paper_scissor_web_app/blob/master/rps.png>
</p>

## Files

There are six files in this repo:

- rps_app_model.py: Python file to load the dataset, build the ML model, and train the model.
- rps_app.py: Python file to build the web-app.
- my_model.hdf5: file contains the trained model architecture and its corresponding weights.
- setup.sh: file to setup your configuration on Heroku.
- requirements.txt: the file to tell Heroku which dependencies you need to build the app.
- Procfile: file to tell Heroku which and how the command and file should be executed.

