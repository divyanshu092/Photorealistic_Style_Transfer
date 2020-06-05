# High-Resolution Network for Photorealistic Style Transfer

Code taken from paper "[High-Resolution Network for Photorealistic Style Transfer](https://arxiv.org/pdf/1904.11617.pdf)" and [Author Implementation](https://github.com/limingcv/Photorealistic-Style-Transfer/tree/master)

I have used Google Colab Environment for the implementation changes.

# Implementation Changes
The implementation changes proposed in this work are:
1. Different layers of the network store different information regarding the content of the image and the style of the image. So, I analysed the importance of each layer and tried a weighted combination. (Task 1)
2. I varied the ratio of content weight to style weight in order to generate images in a vast diversity. (Task 2)
3. I tried different combinations of loss functions in order to improve the content preservation while transferring style. (Task 3)
4. Along with content loss and style loss, I also included Total Variation Loss.(Task 4)
5. In order to fasten the training process, I tried to use adaptive content to style weight ratio. (Task 5)

# Folder details
1. Artistic NST Images contains the results of the implementation of paper "[A Neural Algorithm of Artistic Style](https://arxiv.org/pdf/1508.06576.pdf)"
2. Content-Style Images contains all the images I have used for generating results of various combination of content and style.
3. Content-Style Weight Ratio contains of results of Task 2.
4. Loss Variations contains the results of Task 3.
5. More Results folder contains the results after the best combination of all Tasks on different content and style images.
6. Single Layer Extraction contains the results of Task 1.
7. Swapping Results folder contains swapping between various Artworks, Day-time Translation and FLower images.

# Examples
Here are some results(from left to right are content, style and output):
<!-- 1. Amber-Van-gogh -->
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/README%20Images/Amber-Van-gogh.png?raw=true" width="90%" height="90%" align="center">
</div>
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/README%20Images/Amber-Love.png?raw=true" width="90%" height="90%" align="center">
</div>
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/README%20Images/Turtle-Vassily.png?raw=true" width="90%" height="90%" align="center">
</div>
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/README%20Images/Vassily2-Van-gogh.png?raw=true" width="90%" height="90%" align="center">
</div>
  
# Acknowledgement by Author
Our work is inspired by [Deep High-Resolution Representation Learning for Human Pose Estimation](https://github.com/leoxiaobin/deep-high-resolution-net.pytorch).

The transfer code is based on [Udacity](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/style-transfer).

# Contact
Author's contact (Ming Li limingcv@gmail.com)
<br/>
My contact (Divyanshu Mandowara divyanshu.mandowara92@gmail.com)
