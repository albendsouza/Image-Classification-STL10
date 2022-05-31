# Image-Classification-STL10
In this project, image classification of the test dataset of STL-10 has been done with 2 techniques

       1) Training the CNN model from scratch. Following steps were followed:
                * Prepare the training and testing data.
                * Build the CNN model Architecture
                * Define the model. Select the Optimizer and Loss Function
                * Train the network and save the checkpoints.
                * Test the model.
                
       2) Training a CNN model using using transfer learning
                * Prepare the training and  testing data
                * Apply data augmentation 
                * Use VGG16 as our pre-trained moodel
                * Freeze the weights in the lower convolutional layers
                * Replace the upper layers of the network with a custom classifier
                * Train only the custom classifier layers for the image classification
                * Define optimiser and loss function
                * Train the network
                * Test the model.
                
On comparing the accuracies of model in both techniques, we see that accuracy of CNN model with transfer learning is more. 
Training the model from scratch gives us the accuracy of 41%, whereas, in the case of using pre-trained model, we see a 
significant increase, with accuracy of 91%
