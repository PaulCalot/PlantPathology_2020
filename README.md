# Plant Pathology 2020

This project is based on [Plant Pathology 2020](https://www.kaggle.com/c/plant-pathology-2020-fgvc7/overview) from the preprint available [here](https://arxiv.org/abs/2004.11958).
This project was realized using [pytorch](https://pytorch.org/), a python library to do machine learning.

We managed to have 93% precision for our top model.

The code associated to this project is organized as follow :
* Data augmentation (from pictures directly and performed locally) : data_augmenting.py 
* Dataset creation (the objects understood by pytorch) : creatingDatasets.ipynb
* Model architectures. 

Notebooks :
* resnet50.ipynb
* googlenet.ipynb
* vgg16.ipynb
* efnetb3.ipynb
* processing_resnet50_definitive.ipynb
* processing_resnet50_3classes.ipynb

Unfortunately, our datasets are not available online anymore .

## Authors 

This project is the work of :
[Calot Paul](https://www.linkedin.com/in/paul-calot-43549814b/)
[Allouah Youssef](https://www.linkedin.com/in/youssef-allouah-8ab264190/)
