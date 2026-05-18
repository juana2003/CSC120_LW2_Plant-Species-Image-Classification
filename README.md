A. Project Overview

Brief Description of the Project:

This project involves developing an image classification model that can recognize and differentiate 20 related plant species using Google Teachable Machine. A dataset containing
at least 250 images per species was collected and organized into labeled classes. The model was trained, evaluated, and tested to measure its accuracy and performance in identifying plant 
species based on visual features.

Purpose of the Image Classification Model:

The purpose of this image classification model is to automatically identify plant species from images using machine learning techniques. It aims to demonstrate how computer vision
can be applied to classify plants accurately and how dataset quality, training parameters, and evaluation methods affect model performance.

B. Plant Species Section



![Alt Text](https://github.com/juana2003/Plant-Species-Image-Classification/blob/0cd66d0da878d2658d0cfe12634e0f454021fdff/cactus.jpg)  

 Common Name: CACTUS                        
 Scientific Name: Cactaceae      

 ![Alt Text] (https://github.com/juana2003/CSC120_LW2_Plant-Species-Image-Classification/commit/e09d9e3f496a57aa2b042214a52b3616f9378989#diff-a31f4af1f959fceb4e00ffb3ce4fbd9d1adc492a901736bce422c52182639d1dR1)

Description:
Cacti are a family of succulent plants adapted to survive in dry and arid environments. They store water in their thick, fleshy stems and usually have spines instead of leaves to reduce water
loss and protect against herbivores. Cacti can vary widely in shape, size, and flower color, and they are commonly used for ornamental purposes, landscaping, and sometimes food or medicine.

C. Model Training Details

![Alt Text](https://github.com/juana2003/Plant-Species-Image-Classification/blob/dc8648829c45f95ad54643c8f2a3a2453a4b0d08/Training%20Model%20.jpg)

I chose 50 epochs to ensure that the model has enough opportunities to review and learn the patterns in the dataset without overfitting. 
This number provides a balance between sufficient learning and efficient training time.

The batch size of 16 was selected to balance training speed and accuracy. A moderate batch size allows the model to process a reasonable number of images at a time,
ensuring stable updates to the model weights while keeping the training process efficient.

The learning rate of 0.001 was chosen because it provides a stable and gradual adjustment to the model’s parameters. This prevents large, 
unstable updates that could reduce accuracy while allowing the model to converge effectively during training.

D. Model Evaluation

![Alt Text](https://github.com/juana2003/Plant-Species-Image-Classification/blob/e90648a81bf41ba1ef4eeed4f43ded741fb7a890/Under%20The%20hood.jpg)


E. Model Testing

TEST 1

![TEST 1](https://github.com/juana2003/Plant-Species-Image-Classification/blob/3747df3714dc433c80616957b918ca3be18091ab/Preview%20Test%201.jpg)

TEST 2

![TEST 2](https://github.com/juana2003/Plant-Species-Image-Classification/blob/0c60bfd3d8a2af958fd00ad201c199ba980c0e6f/Preview%20Test%202.jpg)

TEST 3

![TEST 3](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%203.jpg)

TEST 4

![TEST 4](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%204.jpg)

TEST 5

![TEST 5](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%205.jpg)

TEST 6

![TEST 6](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%206.jpg)

TEST 7

![TEST 7](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20test%207.jpg)

TEST 8

![TEST 8](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%208.jpg)

TEST 9

![TEST 9](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%209.jpg)

TEST 10

![TEST 10](https://github.com/juana2003/Plant-Species-Image-Classification/blob/df17e45506e9a6d85c948c8ee0f86c5dd4c5a6a2/Preview%20Test%2010.jpg)



Reflection Questions:

1. How did the number of images per class affect your model’s accuracy? More images per class improved the model’s accuracy because it had more examples to learn from. Classes with fewer images were harder for the model to predict correctly.
2. Which plant species were most commonly misclassified and why? The desert milkweed plant was most commonly misclassified because it has a similar shape to other plants, causing its percentage to be distributed among other species that look alike.
3. How did changing the epochs, batch size, or learning rate affect the training results? Using 50 epochs, a batch size of 16, and a learning rate of 0.001 provided stable learning and balanced accuracy.
4. What challenges did you encounter during dataset collection and labeling? Even though I uploaded 250 images per class, not all of them were included in the training. About 1–10 images per class were missing and were not captured by the system.
5. If you were to improve your model, what specific changes would you make and why? I would add more images and apply data augmentation to make the model more robust. I would also fine-tune the epochs or learning rate to improve overall accuracy.

Link of 20 plants species (https://drive.google.com/drive/folders/1Yp2hWtGn2xr1V-0AZuKZCoUH9gDqbb3r?usp=drive_link)
