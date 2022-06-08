# Cloth_recommendor
Approach for this work can be summarized in the following points:
1. Rescale data

2. Use the pretrained Resnet18 network as feature vector generator

3. Use the feature arrays to calculate similarity by evaluating cosines of these vectors

4. Create top-k lists

5. Use top-k lists and visualize recommendations

I have used pre trained ResNet for this project, primarily due to its ability to deal with the problem of vanishing gradients. I had a small dataset, of around 1000 images,hence I am using a pretrained net for good accuracy. 

This code reads the images from  directory 'bottoms_resized_png'and stores the modified input images in a new folder. After running script,it will ask you to enter the  number of query images and names of those images. Output will look like this:

![download](https://user-images.githubusercontent.com/56195849/172643853-e574df32-e4a6-4737-aa8c-b57644e36589.png)


Things I am unable to do in the given timeframe:
1. Couldn't resize the output image to look pretty.
2. I coudn't play with more nets like AlexNet, VCG-16 etc.

Reasons for incomplete task is I had to go to college daily and study daily due to my end term practical examinations along with viva.
