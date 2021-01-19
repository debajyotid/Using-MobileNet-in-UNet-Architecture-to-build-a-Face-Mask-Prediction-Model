# Using-MobileNet-in-UNet-Architecture-to-build-a-Face-Mask-Prediction-Model
Example of Image Segmentation &amp; Object Detection using UNet Architecture built using MobileNet as base

### WIDER Face Dataset Face Mask Prediction
---
## Using Mobilenet in UNet Architecture to predict Face Masks

WIDER FACE dataset is a face detection benchmark dataset, of which images are selected from the publicly available WIDER dataset. 
We choose 32,203 images and label 393,703 faces with a high degree of variability in scale, pose and occlusion as depicted in the sample images. 
WIDER FACE dataset is organized based on 61 event classes. 

In this project, we are using 409 images and around 1000 faces for ease of computation.

We will be using transfer learning on an already trained model. 
We will use the MobileNet model which is already trained to detect the face attributes.
We will need to train the last 6-7 layers and freeze the remaining layers to train the model for predicting the mask on the face. 
We use the MobileNet as the building block for a U-Net Architecture.
