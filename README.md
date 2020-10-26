# Covid-prevention-device

This project contains three parts:

1)collecting and training images
      collecting image from the user and training the image and creating the model.Image taken for a user 80 grayscale image which is stored in your directory.
      
2)Training image for mask detection
      using convolution neural network the mask can be trained with the help of kaggle mask detection dataset as a source. It trains the images wth or without mask and create the model.
      
3)Mask and face detection
      First it checks for the mask is weared or not . if the mask is weared it will check for face and recognize the member which is trained in the first part.If the mask is not weared it prints "please wear mask and come"
