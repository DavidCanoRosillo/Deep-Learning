## Unpaired image to image translation with CycleGan:
The objective is to turn a horse image to a zebra image while retaining pose information. Here are some examples transforming horses to zebras and viceversa.

## Horse -> Zebra
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/CycleGan/results/Screenshot%202022-04-18%20at%2012.03.07.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/CycleGan/results/Screenshot%202022-04-18%20at%2012.03.35.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/CycleGan/results/Screenshot%202022-04-18%20at%2012.04.29.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/CycleGan/results/Screenshot%202022-04-18%20at%2012.04.39.png)

## Zebra -> Horse
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/CycleGan/results/Screenshot%202022-04-18%20at%2012.03.44.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/CycleGan/results/Screenshot%202022-04-18%20at%2012.03.55.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/CycleGan/results/Screenshot%202022-04-18%20at%2012.20.01.png)
![alt text](https://github.com/DavidCanoRosillo/GANS/blob/master/CycleGan/results/Screenshot%202022-04-18%20at%2012.16.05.png)


## Abstract of the paper:

Image-to-image translation is a class of vision and graphics problems where the goal is to learn the mapping between an input image and an output image using a training set of aligned image pairs. However, for many tasks, paired training data will not be available. We present an approach for learning to translate an image from a source domain X to a target domain Y in the absence of paired examples. Our goal is to learn a mapping G:X→Y such that the distribution of images from G(X) is indistinguishable from the distribution Y using an adversarial loss. Because this mapping is highly under-constrained, we couple it with an inverse mapping F:Y→X and introduce a cycle consistency loss to push F(G(X))≈X (and vice versa). Qualitative results are presented on several tasks where paired training data does not exist, including collection style transfer, object transfiguration, season transfer, photo enhancement, etc. Quantitative comparisons against several prior methods demonstrate the superiority of our approach.
https://arxiv.org/abs/1703.10593
