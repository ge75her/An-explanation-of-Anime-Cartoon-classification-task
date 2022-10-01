# An-explanation-of-Anime-Cartoon-classification-task
Anime and Cartoon both are a form of animation and look almost the same, but there are some structural differences. Although it is hard to explain, human can easily recognize which images are from cartoon class and which images from anime class. In this repo we will finish two tasks. First, we will use ResNet50 network to complete this binary classification task, after that, we will visualize the points which the machine mainly focus on to explain this model. Here, we choose Saliency map, LIME and Grad-CAM to visulize the highlight area. 
## Setup
- download dataset on [Kaggle](https://www.kaggle.com/datasets/kanakmittal/anime-and-cartoon-image-classification). <br>
- download repo
- run `training.ipynb` file to training the model, save the output chackpoint in `./logs' folder
- run `CNN explanation.pynb` file, observe the visual explanation based on Saliency map, LIME and Grad-CAM
## Results
## Saliency maps
