# ResNet-for-fine-grained-classification

## Usage
The script would firstly trains the ResNet101 model, and then build up a .csv file named *submission.csv* to write down the predictions. You can change the model to be SpinalNet by modifying the line 272, 273 in the script. Note: Specify the correct number of class in variable *Num_class* with the spinalNet mode, or in the parameter *out_features* with ResNet model mode. 
