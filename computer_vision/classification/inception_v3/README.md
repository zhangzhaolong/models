*******************************************************************************
##### Structure of the directory for storing model files
```
computer_vision
   |-- classification
       |-- inception_v3
            |--inception_v3.om
            |--README.md
   |-- object_detect
   |-- segmentation
```
*******************************************************************************

#### Model Description

Image classification inference model

##### Original Network Link:

https://drive.google.com/open?id=0B9mkjlmP0d7zTEJmNEh6c0RfYzg

##### Pre-trained Model Link:

https://drive.google.com/open?id=0B9mkjlmP0d7zTEJmNEh6c0RfYzg

##### Input Data Description:

The input image should be resized to 299*299 pixels, and padding to 384*304 pixels, YUV420SP_U8.

##### Out Data Description:

The pre-trained model is trained for image recognition, and its results should add 2, then follow 1000 lables of synset.txt in https://drive.google.com/open?id=0B9mkjlmP0d7zTEJmNEh6c0RfYzg.

##### Custom Operator:

Not included

##### Versions that have been verified: 

- Atlas 200
- Atlas 300
