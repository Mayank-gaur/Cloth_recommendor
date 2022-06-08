# Cloth_recommendor
Approach for this work can be summarized in the following points:
1. Rescale data

2. Use the pretrained Resnet18 network as feature vector generator

3. Use the feature arrays to calculate similarity by evaluating cosines of these vectors

4. Create top-k lists

5. Use top-k lists and visualize recommendations

I have used pre trained ResNet for this project, primarily due to its ability to deal with the problem of vanishing gradients. I had a small dataset, of around 1000 images,
 hence I am using a pretrained net for good accuracy. 
