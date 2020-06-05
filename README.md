# Face-recognition

## Aim of the project

The main goal of this project was to take the celab dataset (https://www.kaggle.com/jessicali9530/celeba-dataset), take some features and build algorithms able to learn some characteristics of a face. 

## Variables and models
Here, I've choosen to take those following attributes :
- Attractive
- Bald
- Blackhair
- Smiling
- Straigth Hair
- Wavy Hair
- Young
- Eyeglass
- Gray Hair
- Blond Hair
- Pale Skin
- Male
- No Beard
- Mustach
- Brownhair

Some of the models constructed were kind of the same because the target variable didn't change very much (Blond hair and Black hair for instance). However, some models as the one for "Smilling" needed a more complex shape of neural networks (two branches at the begining of the network, the first one looking at the upper part of the face and the second one looking at the lower part). 

## Results

The results are concatenated in the Consolidated_Models.ipynb file (notebooks folder) where the models are tested on random faces.


