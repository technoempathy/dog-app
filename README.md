### Dog App
# Pick the best dog to go with your outfit

#### Dog breed classifier computer vision project using CNN transfer learning for Udacity Deep Learning Nanodegree

###### Disclaimer: Here’s a picture of my dog, Oscar. Obviously, like any dog, he is a canine person and not an accessory.  

![My dog, Oscar is a Pug/Boston terrier](/Osc.jpg "Title")

## Getting Started
### Step 1: Review my code and results in [dog_app.ipynb](https://github.com/technoempathy/dog-app/blob/master/dog_app.ipynb "Title").

### Step 2: Do this project yourself
To make your own Dog App review the project requirements, go [here](https://github.com/udacity/deep-learning-v2-pytorch/tree/master/project-dog-classification "Title") and follow the instructions in the README.

## Prerequisites
1. Jupyter Notebooks
2. GPU
3. The [dog dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip "title"). (“Unzip the folder and place it in the repo, at location path/to/dog-project/dogImages. The dogImages/ folder should contain 133 folders, each corresponding to a different dog breed.” – @udacity)
4.	The [human dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz "Title"). (“Unzip the folder and place it in the repo, at location path/to/dog-project/lfw.” -@udacity) 
5.	PyTorch and Torchvision. For installation instructions see [Udacity's README in the Deep Learning repository](https://github.com/udacity/deep-learning-v2-pytorch "Title").
6.	Your own images. I recommend at least 2 test images in each of the following categories: dogs, humans, cats, other. Each image should be center-cropped and no image should contain both a dog and a human.

## Known Issues
* The human-detector (code provided by Udacity) is not very accurate and therefore interferes with the accuracy of the app as it was intended. Thus, once the rest of the cells have been run, I find it better to just run the following code, using the image of a human. The algorithm will then return the breed that best matches the human’s outfit. :smile:

```
def human_app(img_path):
    print("Hello, human!")
    image = imread(img_path)
    plt.imshow(image)
    breed = predict_breed_transfer(img_path)
    print("You resemble a " + breed + "!")
 
 human_app("imagepath")
 ```

## Authors
- @technoempathy – Layla Messner 

## Acknowledgments
-	@udacity for the project, starting code, and instructions for downloading the datasets
-	@facebook for the scholarship to the Udacity Deep Learning Nanodegree
