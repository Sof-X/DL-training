# Simple
Contains summary of the code files 

## SimpleNN
using cifar10 dataset ( the URL to download the dataset is already in a library so u don't need it) [quick and easy]
- We define the classes
- Create NN and CNN with *models.Sequential* and Compile , *Train* with model.fit [] (automatically does backprop and other functions, even batch size)
- **Classification Report**
- model.Evaluate uses the trained model and feeds it the x_test data and then compares prediction to y_test without updating the weights.(like doing 1 more epoch)
  
## BasicNN
Neural Network that classifies Setosa,Versicolor,Virginica [manual control]
- use torch.nn and class to make the model
- take data from URL , in .csv file
- *Train* with for loop (model.forward), manually [] add backprop , NO BATCHES
- append loss of final image in an epoch and plot
- Manual Evaluation
- ***Save and Load Model***
