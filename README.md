# Chest-Xray-FastAI
 Image Classification of Chest X-Ray to detect pneumonia

 ![Clean X-Ray](https://github.com/bsamaha/Chest-Xray-FastAI/blob/master/Images/normal.jpeg) ![Pneumonia](https://github.com/bsamaha/Chest-Xray-FastAI/blob/master/Images/pneumonia.jpeg)

# Summary:
This classifier was created using the Fastai library which is built upon Pytorch. In this project I have built a model from the Chest X-Ray dataset curated by Kaggle to predict if a patient has pneumonia using chest x-ray images. There was a total of about ~5000 images with a total size of just over 1 GB. This model used transfer learning and started with the ResNet34 architecture and was fine tuned for this case. Transfer learning allowed for faster training time, and cultivated a more accurate model that needed less data than from scratch. The final result was an image classification project that was able to detect pneumonia with ~92% accuracy overall.

This repo was made to coincide with the blog post 
[Deep Learning Image Classification with Fast.ai](https://towardsdatascience.com/deep-learning-image-classification-with-fast-ai-fc4dc9052106). 

The data set is from the [Kaggle Chest X-Ray Images 
(Penumonia)](https://www.kaggle.com/paultimothymooney/chest-xray-pneumonia)

If you have any questions about this repo please contact me by one of the following:
- email: Blake.samaha16@gmail.com
- linkedin: https://www.linkedin.com/in/blakesamaha/
- Twitter: @Mean_Aggression
