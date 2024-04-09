# Project: Pet Image Classifier

## Description:

This project is a pre-trained image classifier that can identify dogs and cats in images. The project was developed as part of the Udacity AI Programming with Python - Bertelsmann program.

### Main Codebase:

The main codebase for this project was obtained from the Udacity AI Programming with Python - Bertelsmann program. The code has been cloned for submission purposes and to easily run on a local machine.

### Installation:

To install the project dependencies, run the following command:

```sh
pip install pytorch pillow
```

## Usage:

#### To run the project, follow these steps or use run_models_batch.sh:

```sh
# Run the following command to check the images using the ResNet model:
python check_images.py --dir pet_images/ --arch resnet --dogfile dognames.txt

# Run the following command to check the images using the AlexNet model:
python check_images.py --dir pet_images/ --arch alexnet --dogfile dognames.txt

# Run the following command to check the images using the VGG model:
python check_images.py --dir pet_images/ --arch vgg --dogfile dognames.txt

# The output from each run will be piped into a text file.
```



### Note:

The images for the pet images dataset are already included in this repository.
