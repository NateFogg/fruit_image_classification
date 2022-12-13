# Directions: Please run the code blocks in order on the notebook

# fruit_classification.ipynb 
* This contains all the code necessary to read data, add noise, train model, check accuracy, etc. (best to use Colab for training and data loading)
Code Blocks 1-6: connect your drive and import necessary libraries 
Code Blocks 7-9: read in the fruit names and image data
Code Block 10: shows a random choice of an image in the data and prints it
Code Block 11-12: manually add noise to each image, show image of example noisey image
Code Block 13: preprocess data, normalize it, split testing and training, create model, and train model
Code Block 14: Not necessary to run, checking the model prediction accuracy
Code Block 15-19: Model evaluation and metrics
Code Block 20: graph showing noisey data
Code Block 21: More metrics
Code Block 22+: Playing around with other images, not necessary to run!


# proj.ipynb & new_trained_model.h5 
* This is the code we used for the CS Fair demonstration (we ran this locally to access computer camera)
* proj.ipynb runs a script which accesses your computer camera and feeds it to the model in real time to provide a classification
* new_trained_model.h5 is the saved trained model so you can avoid having to train locally


