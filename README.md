# Deep-Learning-for-Healthcare
Automated methods to detect and classify human diseases from medical images.

This repository contains solutions to better diagnosis of serious diseases using Deep Learning Techniques.
Currently two diseases are being targeted here:

1. **Diabetic Retinopathy** :  is a diabetes complication that affects eyes. It's caused by damage to the blood vessels of the light-sensitive tissue at the back of the eye (retina). It is the leading cause of blindness in the working-age population of the developed world. It is estimated to affect over 93 million people.
The problem aims as identifying signs of diabetic retinopathy in eye images for which different Convolutional Neural Network Architechtures have been experimented with.

2. **Pneumonia** : Detection of Pneumonia using chest x-ray images. According to the World Health Organization (WHO), pneumonia kills about 2 million children under 5 years old every year and is consistently estimated as the single leading cause of childhood mortality, killing more children than HIV/AIDS, malaria, and measles combined.
Again CNN models have been used to classify the chest x-ray image as being normal or not. 

For both these problems Transfer Learning Framework has been used. Different models like VGG16,InceptionV3 and Xception which are trained on the Imagenet dataset have been used as base models in these.
Transfer Learning offers an effective solution to create models with high accuracy and sensitivity in short amount of time and promote better diagnosis of health issues even with limited amount of clean and labeled medical data available today.
