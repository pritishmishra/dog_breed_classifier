# Dog Breed Classifier Application

## What this is?
The objective of the project is to build a dog-breed classifier. The algorithm developed as part of the project could be used as part of a mobile or web app. At the end of this project, the program will accept any user-supplied image as input. If a dog is detected in the image, it will provide an estimate of the dog's breed. If a human is detected, it will provide an estimate of the dog breed that is most resembling.

The project uses CNN models to perform the classification task.

More details about the project can be found in this Medium blog.

## How to use this?
If you just want to view the results, you can check out the Jupyter notebook or the html version of the report.

If you want to use the project to re-train the model or re-run the application:
- Pre-requisite: Jupyter Notebook, Anaconda environment (preferably), Python Libraries used by the project
- Dataset: [Human-images dataset](http://vis-www.cs.umass.edu/lfw/lfw.tgz), [Dog-images dataset](https://s3-us-west-1.amazonaws.com/udacity-aind/dog-project/dogImages.zip)
- Unzip the folders and place it in the repo, at location path/data/dog_images and path/data/lfw for dog-images and human-images directories respectively.
- Open a terminal window and navigate to the project folder. Open the notebook and follow the instructions.
```
jupyter notebook dog_app.ipynb
```
