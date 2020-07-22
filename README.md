# FashionSimulator

Using one of the state of art techniques to build a generative model which has been trained on fashion mnist data sets.

AIM:

The model aims to generate fake samples of the existing mnist fashion data set having alike probability distribution.
To contribute to the fashion world by generating samples without any human interference which can be helpful for new designs for the leading fashionmakers.

Frameworks and Model:

The model is inspired from the Vanilla or plain gan model of the goodfellow paer of GAN in nips 2016 
paper: https://www.semanticscholar.org/paper/NIPS-2016-Tutorial%3A-Generative-Adversarial-Networks-Goodfellow/2c740e574eea66fdcf473e15ed2c228baef2eccd

This modeled has been altered for making it fit for various conditions in order to make a conditional GAN , so that the model is able to produce specific samples.
The model has been trained on colab using tensorflow library on various epochs and debugged according to needs.
The results have been compared from the plain GAN model and other pre existing models.
The final step is to convert the it into tensorflow lite model to deploy it to an app.


Results and further scope:

An application which can generate any number of unique samples for any category of a fashion data set has been created and added to the repo.
The training has been done of B/W images but the model can be further integrated to a RGB picture generating model.
The similar schema can also be used in the field of tabular data generation by taking some insights of the ongoing research around the globe.


## Model Type Conversion

The model was converted into a TFLite model using the TFLiteConverter for deploying it to android Apps.

## Fashion Simulator App

- This app generates images for different articles of clothing.
- It uses the C-GAN model for image generation.
- The app displays a variety of options for the type of article(ex- Shirt, shoes, etc) which user can select.
- Then the app displays a single brand new image generated from the model.
- More articles of the same type can be generated by clicking on the "+" icon in the menu.
- The images of the generated articles can be saved to the device using the "save" icon in the menu.

# App Permissions

- WRITE EXTERNAL STORAGE
