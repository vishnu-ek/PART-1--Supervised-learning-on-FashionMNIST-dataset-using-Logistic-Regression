The code in this prepository involves in exploring the fashion mnist dataset using Logistic regression.

About Data:
1) Fashion Mnist dataset is from Zalando. It consists of 60,000 training instances and 10,000 testing instances.
2) Each of the training and testing instances is a grayscale image
3) 10 classes are associated with the target feature

Pytorch api has been used to build the logistic regression model both with l1 and l2 regularisation.
Training accuracy, testing accuaracy, number of learnable parameters and time taken to train the model are determined to evaluate the model.
A plot of confusion matix has been made for the predictions on the test dataset.

The data can either be obtained from the torchvision dataset module or can be downloaded as a csv file from the following link.
https://developer.ibm.com/technologies/artificial-intelligence/data/fashion-mnist/
