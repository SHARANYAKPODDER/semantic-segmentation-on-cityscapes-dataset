# semantic-segmentation-on-cityscapes-dataset

I have done semantic segmentation on CityScapes dataset. The dataset is huge that's why I haven't uploaded it overhere. You can download the dataset by creating an account in CityScapes and then you can download it. You will need GPU to run the model used by me. I have used segmentation_models from pytorch and used UNET for training, encoder used - resnet34. One can use other encoders as well. I used imagenet as pre-trained weights. After training I fit the model and stored that in a file. Finally, I tested it with "val" dataset. Lastly I have plotted the input mask, ground mask and the predicted mask. 

This semantic segmentation task was inspired by TALHA ANWAR (https://github.com/talhaanwarch).
But I have used the evaluation metrics in a detailed way. I have changed the hyperparameters as well.
