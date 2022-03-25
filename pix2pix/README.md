Pix2pix image to image translation for paired images from the paper https://arxiv.org/abs/1611.07004. I trained the model on 2 datasets one is composed of black and white images and their color pair. The other dataset has segmented images of a street and the real image from which those segments where produced. The generator model is given as input the segments and generates a plausible street image corresponding to that segment. It is a type of conditional gan.
![Model architecture](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/auxiliar_images/pix2pix_architecture.jpeg)
Results on segment images (Left is segment, middle is generated, right is real street):

Results on gray images (Left is gray, middle is generated, right is real color image):
![alt text](https://github.com/DavidCanoRosillo/GANS/tree/master/pix2pix/gray2color_images#:~:text=Screenshot%202022%2D03%2D24%20at%2010.31.07.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/gray2color_images/Screenshot%202022-03-24%20at%2010.35.23.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/gray2color_images/Screenshot%202022-03-24%20at%2010.35.23.png)
