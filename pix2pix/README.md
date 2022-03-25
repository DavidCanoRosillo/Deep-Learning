Pix2pix image to image translation for paired images from the paper https://arxiv.org/abs/1611.07004. I trained the model on 2 datasets one is composed of black and white images and their color pair. The other dataset has segmented images of a street and the real image from which those segments where produced. The generator model is given as input the segments and generates a plausible street image corresponding to that segment. It is a type of conditional gan. You can check all the outputs of the notebooks in these links:
segment2street: https://www.kaggle.com/code/davidcanorosillo/pix2pix
gray2image: https://www.kaggle.com/code/davidcanorosillo/pix2pix-landscapes

![Model architecture](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/auxiliar_images/pix2pix_architecture.jpeg)

Results on segment images (Left is segment, middle is generated, right is real street):
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/segment2street_images/Screenshot%202022-03-25%20at%2010.54.12.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/segment2street_images/Screenshot%202022-03-25%20at%2010.55.32.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/segment2street_images/Screenshot%202022-03-25%20at%2010.55.19.png)

Results on gray images (I also tried it on some gray images from google):
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/gray2color_images/Screenshot%202022-03-24%20at%2010.35.23.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/gray2color_images/Screenshot%202022-03-24%20at%2010.31.07.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/pix2pix/gray2color_images/Screenshot%202022-03-24%20at%2010.31.28.png)
