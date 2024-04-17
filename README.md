# Classify-advertisement-images-and-read-text-using-computer-vision-and-OCR-techniques
In this code, I have build a model which can classify if the input image is advertisement of any brand or not. It will also identify any logo or text from image and also read the text from image.
To do this project, I followed below steps:
-create image dataset : both positive and negative images to create haar cascade file.
-data cleaning : write a code to remove duplicate images from location
-separate positive & negative images
-create haar cascade file : i used Cascade-Trainer-GUI to create haar cascade file. I had to retry again and again with new images to improve the accuracy
-model building : I tried fine tuning techniques like, Grayscaling, blurring, denoising etc to reach best result. I had to create haar cascade file few times to get better accuracy.
-text identification : i created different environment to use easyocr package as it doesn't work properly in python 3.7(prefer python 3.8)
