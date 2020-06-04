# High-Resolution Network for Photorealistic Style Transfer

Code incorporated from paper "[High-Resolution Network for Photorealistic Style Transfer](https://arxiv.org/pdf/1904.11617.pdf)".

I have used Google Colab Environment for the code.

# Implementation Changes
The implementation changes proposed in this work are:
1. Different layers of the network store different information regarding the content of the image and the style of the image. So, I analysed the importance of each layer and tried a weighted combination. (Task 1)
2. I varied the ratio of content weight to style weight in order to generate images in a vast diversity. (Task 2)
3. I tried different combinations of loss functions in order to improve the content preservation while transferring style. (Task 3)
4. Along with content loss and style loss, I also included Total Variation Loss.(Task 4)
5. In order to fasten the training process, I tried to use adaptive content to style weight ratio. (Task 5)

# Folder details
1. Artistic NST Images contains the results of the implementation of paper "[A Neural Algorithm of Artistic Style]"
2. Content-Style Images contains all the images I have used for generating results of various combination of content and style.
3. Content-Style Weight Ratio contains of results of Task 2.
4. Loss Variations contains the results of Task 3.
5. Single Layer Extraction contains the results of Task 1.
6. Swapping Results folder contains swapping between various Artworks, Day-time Translation and FLower images.

# Examples
Here are some results(from left to right are input, style and output):
1. Amber-Van-gogh
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Content-Style%20Images/Amber.png?raw=true" width="25%" height="15%" align="left">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Content-Style%20Images/Van-Gogh.jpg?raw=true" width="25%" height="25%" align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/More%20Results/Amber_Van-gogh_cosine_loss2_1000_total-var_4e-4.png?raw=true" width="25%" height="15%" align="right">
</div>
2. Amber-Love
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Content-Style%20Images/Amber.png?raw=true" width="25%" height="25%" align="left">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Content-Style%20Images/Love.png?raw=true" width="30%" height="15%" align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/More%20Results/Amber-love_all_adaptive.png?raw=true" width="25%" height="25%" align="right">
</div><!-- 
3. Turtle-Vassily
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/More%20Results/Turtle.jpg?raw=true" width="31%" height="30%" align="left">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Content-Style%20Images/Vassily.jpg?raw=true" width="31%" height="30%" align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/More%20Results/Turtle-Vassily.png?raw=true" width="31%" height="30%" align="right">
</div>
4. Vassily2-Van-gogh
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Content-Style%20Images/Vassily2.jpg?raw=true" width="31%" height="30%" align="left">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Content-Style%20Images/Van-Gogh.jpg?raw=true" width="31%" height="30%" align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Swapping%20Results/Vassily2_to_Van-gogh.png?raw=true" width="31%" height="30%" align="right">
</div>
 -->
<!-- 
# Acknowledgement
Our work is inspired by [Deep High-Resolution Representation Learning for Human Pose Estimation](https://github.com/leoxiaobin/deep-high-resolution-net.pytorch).

The transfer code is based on [Udacity](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/style-transfer).
 -->
# Contact
Author's contact (Ming Li limingcv@gmail.com)
My contact (Divyanshu Mandowara divyanshu.mandowara92@gmail.com)
