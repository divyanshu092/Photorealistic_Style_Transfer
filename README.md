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
Artistic NST Images contains the results of the implementation of paper "[A Neural Algorithm of Artistic Style]"
Content-Style Images contains all the images I have used for generating results of various combination of content and style.
Content-Style Weight Ratio contains of results of Task 2.
Loss Variations contains the results of Task 3.
Single Layer Extraction contains the results of Task 1.
Swapping Results folder contains swapping between various Artworks, Day-time Translation and FLower images.

# Examples
Here are some results(from left to right are input, style and output):
<br/><div align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/More%20Results/Turtle.jpg?raw=true" width="31%" height="30%" align="left">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/Content-Style%20Images/Vassily.jpg?raw=true" width="31%" height="30%" align="center">
<img src="https://github.com/divyanshu092/Photorealistic_Style_Transfer/blob/master/More%20Results/Turtle-Vassily.png?raw=true" width="31%" height="30%" align="right">
</div>
<!-- <br/><div align="center">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Church/content.png" width="31%" height="30%" align="left">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Church/style.png" width="31%" height="30%" align="center">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Church/output.png" width="31%" height="30%" align="right">
</div>
<br/><div align="center">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Harbor/content.png" width="31%" height="30%" align="left">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Harbor/style.png" width="31%" height="30%" align="center">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Harbor/output.png" width="31%" height="30%" align="right">
</div>
<br/><div align="center">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Amber/content.png" width="31%" height="30%" align="left">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Amber/style.png" width="31%" height="30%" align="center">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Amber/output.png" width="31%" height="30%" align="right">
</div>
<br/><div align="center">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Ocean/content.png" width="31%" height="30%" align="left">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Ocean/style.png" width="31%" height="30%" align="center">
<img src="https://github.com/limingcv/Photorealistic-Style-Transfer/blob/master/supplementary_material/more_results/Ocean/output.png" width="31%" height="30%" align="right">
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
