# Semantic Segmentation of Cars and Roads
This submission has been revised from the advices of teacher Tran Nguyen Ngoc, some updates are made as follows:
- Reuse U-Net implementation from Peter Giannakopoulos, which is made some changes from the base model (Unlike the U-Net diagram above (which has 5 downsampling levels), Peter implemented U-Nets with different numbers of downsampling levels, from 5 to 8 downsampling steps. Peter has also added BatchNormalization on every convolution step).
    - Some modifications of mine: rewrite the comiple part to load model faster and update the loss function.
- I infered an gif for 1000 images for better visualization of model's prediction.

# Folder:
- augmentation: used for augmentation part
- loss: used for customizing loss funtions
- model: implement U-Net model
- test_output.gif: used for video visualization
- U-Net: used for training model