# smiley-recognition

This is a small project about a machine learning model that can recognize four different kinds of smileys drawn on an 28x28 grid.  
![alt text](https://github.com/KonKli/smiley-recognition/blob/main/happy.png)
![alt text](https://github.com/KonKli/smiley-recognition/blob/main/sad.png)
![alt text](https://github.com/KonKli/smiley-recognition/blob/main/neutral.png)
![alt text](https://github.com/KonKli/smiley-recognition/blob/main/surprised.png)

# data generation

The image data that gets fed to the model later is created by chosing random components to create a smiley face. More specifically each generated image consists of a mouth, a left eye, a right eye and sometimes a nose. The parts are chosen from the images stored in data\test-data-source or data\train-data-source. The test images are created from a different source than the training data to get a better approximation on how good the model really works.  
![alt text](https://github.com/KonKli/smiley-recognition/blob/main/data/train-data-source/happy-mouth/1.png)+
![alt text](https://github.com/KonKli/smiley-recognition/blob/main/data/train-data-source/left-eye/15.png)+
![alt text](https://github.com/KonKli/smiley-recognition/blob/main/data/train-data-source/right-eye/13.png)=
![alt text](https://github.com/KonKli/smiley-recognition/blob/main/happy.png)

# training the model

The model is a Canovolutional Neural Network and I just experimented with the architecture until it had an accuracy of over 90% on the test data.

# try it yourself
