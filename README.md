# Image Denoising using Autoencoders in Denoising-Images-with-Autoencoders

## Data Collection:
--> The Olivetti Faces Dataset was employed as the dataset.

--> This dataset comprises 400 images, with 10 distinct images for each of the 40 subjects.

--> Image dimensions are 64x64.

## Introducing Noise:
--> The primary task involves adding noise to images.

--> Python code was utilized to inject random noise into all 400 images.

--> Division of data led to a split of 320 and 80 images for training and testing correspondingly.

## Constructing the Model:
--> This step holds significant importance in achieving successful denoising.

--> A Convolutional Autoencoder was chosen, leveraging CNN's feature extraction capabilities, crucial for this task.

--> After experimentation, the best outcomes were obtained with 1000 epochs, though attempts were made with 100 and 500 epochs.

## Model Assessment:
--> Post-training and testing, evaluation of model performance was undertaken.

--> Prediction of noisy test images and subsequent comparison with original test images were conducted as demonstrated in the code.

--> The reconstructed image displays retained features, albeit with slight blurring due to the small image size.
