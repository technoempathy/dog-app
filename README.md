# Pick the best dog to go with your outfit

###### Dog breed classifier computer vision project using CNN transfer learning for Udacity Deep Learning Nanodegree

Disclaimer: Here’s a picture of my dog, Oscar. Obviously, like any dog, he is a canine person and not an accessory.  

![My dog, Oscar is a Pug/Boston terrier](/Osc.jpg "Title")

## Getting Started
### Option 1: Review my code and results in [dog_app.ipynb ](https://github.com/technoempathy/dog-app/blob/master/dog_app.ipynb "Title").

### Option 2: Do this project yourself
To make your own Dog App review the project requirements, go [here](https://github.com/udacity/deep-learning-v2-pytorch "Title") and follow the instructions in the ReadMe.

## Prerequisites
Adapted from the [Udacity Readme for this project ](https://github.com/udacity/deep-learning-v2-pytorch "Title")
1.	The dog dataset. (“Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages. The dogImages/ folder should contain 133 folders, each corresponding to a different dog breed.” – @udacity)
2.	The human dataset. (“Unzip the folder and place it in the repo, at location path/to/dog-project/lfw.” -@udacity) 
3.	Pytorch and Torchvision. For installation instructions see @udacity’s [README in the program repository ](https://github.com/udacity/deep-learning-v2-pytorch “Title” )
4.	Your own images. I recommend at least 2 test images in each of the following categories: dogs, humans, cats, other. Each image should be center-cropped and no image should contain both a dog and a human.

## Known Issues
* The human-detector (code provided by Udacity) is not very accurate and theefore interferes with the accuracy of the app as it was intended. Thus I find it better to just run the following code, using the image of a human. The algorithm will then return the breed that best matches the human’s outfit. :smile:

## Authors
-	@technoempathy – Layla Messner 
-	@udacity

## Acknowledgments
-	@udacity for the project and starting code (and the list of prerequisites)
-	@facebook for the scholarship to the Udacity Deep Learning Nanodegree
