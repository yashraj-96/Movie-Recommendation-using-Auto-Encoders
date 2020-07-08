# Movie-Recommendation-System-using-Auto-Encoders
Stacked Auto-Encoders are used for implementing a movie recommendation system. This model predicts the ratings by the user in a range from 1 to 5 instead of binary prediction. This makes it even more powerful than Boltzmann Machine.

# Dataset

The dataset comprises of 1,00,000 movies which correspond to those three .dat files (movies.dat , ratings.dat, users,dat) 

The train and test data correspond to the base and text files with the name 'U1'.


Stacked Auto-Encoders are one of the most advanced technologies used in recommendation systems. They are implemented with a class which comprises of functions to build the architecture step by step. This project is implemented with PyTorch which is more powerfu as compared to Keras, so the training phase takes not more than 5 minutes. The testing phase is carried out with only one epoch over entire dataset of movies , which provieds a RMSE(Root Mean Square Error) loss of 0.94.

Thus, if a user gave a rating for a certain movie as 3 stars, the model would predict it as 2 - 2.5 stars with the stated loss which is quite acceptable and feasible.

Thoroughly enjoyed implementing my first Stacked - Auto - Encoder project.
