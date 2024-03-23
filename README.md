# mvi-sp
A Medium blogpost about GAN training in general and some of my thoughts can be found here https://medium.com/@veronikakalouskov/generative-adversarial-network-training-for-dummies-db1ef90d568a.

### MeowGAN
The aim of this project is to build a conditional generative adversarial network (CGAN), capable of generating images of specific cat breeds. The goals on which this functionality will be evalueated are the networks ability to generate plausible looking cat images and its ability to generate specific breeds based on label input. For the first checkpoint the goal was to create a generative adversarial network (GAN), which was then turned into a CGAN for the final submisssion. 

### Data
The data is downloaded directly from Kaggle in the project notebook, the only requirement to be able to do this is to copy the kaggle.json file located in the mvi-sp/config folder to your Google Drive /content/drive/MyDrive root folder.

### Run
The only requirement for running the project in Google Colab is to copy the cat_detector.xml file located in the mvi-sp/config folder to your Google Drive /content/drive/MyDrive root folder. This will enable the correct use of OpenCV Cascade Classifier, used for image preprocessing. The whole project can be run directly in the Jupyter notebook, it is recommended to use the GPU accelerator option, otherwise it would take ages to run the whole project.