The following repo showcases Collaborative Filtering based Recommendation System implemented from Scratch. The dataset has been gathered from Kaggle.

Collaborative Filtering develops 2 vectors. One is the parameter vector for every user and a feature vector for every movie.
The cost function has been computed taking these into consideration. However to update the parameters the derivative of the cost function is not straight forward unlike basic regression techniques. Hence we use the tf methods to implement the derivative of the cost functions. The updations of the feature vector and the parameter vector are updated using the process of Gradient Descent.

Finally the predicted and actual ratings are also printed in the notebook for comparison purposes.