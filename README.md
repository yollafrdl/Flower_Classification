# Flower Classification
Final project of Digital Image Processing. The python library used for this project are opencv, sckikit-learn, keras, pickle, matplotlib, and numpy.

## Data
The data used for this project was from https://www.robots.ox.ac.uk/~vgg/data/flowers/17/index.html. In this project, we only used 5 classes with 40 images for each class. The sample image of each class shown below
![image](https://user-images.githubusercontent.com/37945491/145161784-6c7a919c-ae31-41f1-b5dc-dadb5f25a961.png)

## Classification Process
There are 5 steps for this process :
1. Find the ROI and crop the image using opencv (Preprocess.ipnyb)
![image](https://user-images.githubusercontent.com/37945491/145164658-e9834b48-bda4-460e-8d7e-f145473f4cce.png)
2. Segmenting the flower using opencv (Preprocess.ipnyb)
![image](https://user-images.githubusercontent.com/37945491/145165422-2af0555e-24ab-44a3-aac2-626641406a8d.png)
3. Resize the image into 250 x 300 (Preprocess.ipnyb)
4. Augmented it by horizontally flip the images, change the rotation with range 40, and change the brightness into 0.5 - 1 using keras ImageDataGenerator (Augmentation-flowers-data.ipynb)
5. Flower classification using keras CNN. The CNN's architecture are shown below. (Flower-classification-CNN.ipynb)
![image](https://user-images.githubusercontent.com/37945491/145165589-54e5bb71-65c4-49bd-a88a-eae4aed342a7.png)


