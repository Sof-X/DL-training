## MAIN

# DeepCNN_Renotte
Create a Happy-Sad classifier with images from google
- set the GPU memory Consumption Growth
- upload images from zip file to colab and unzip (choose the file), too long time to upload
- **Delete File**
- remove dodgy images that don't match extensions we want
- Get tensorflow API, and with keras, builds an image dataset for you (labels,classes,batch,img size) and does preprocessing
- Preprocess Data, use *.next* , **SPLIT DATA**
- Build Sequential model and use *model.add*
- train with Validation Data using *.fit* and plot *Loss* and *Accuracy*
- Precision,Recall,BinaryAccuracy
- Save model

# Data Augmentation
Create a flower classifier and Improve Training with augmentation
- Download data from an URL (.tgz file) and store it in a folder in colab
- Use PIL library
- search for files in folder based on name
- Use **Dictionaries** for Images and Labels
- resize and train Sequential model with *.compile* and *.fit*
- get a **SOFTMAX** output
- Improve Training with **Augmentation** , ADD two layers to the model 1 for augmentation and 1 for Dropout
