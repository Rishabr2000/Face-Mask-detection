Question 1 
The Jupyter Notebook file (.ipynb format) that contains the code for 
the first question is kept in the 'question 1' folder. Upon code 
execution, a 2-dimensional numpy array with the data type 'float64' is 
produced. The Jupyter Notebook environment displays the output 
immediately. 

Question 2 
The Jupyter Notebook file (.ipynb format) that contains the code for 
the second question is kept in the ‘question 2’ folder. The outputs of 
all three test cases is stored in the same folder and the format of the 
folder is (.csv) as the code and is named as follows: 
Test Case 1 [1,1] – histogram_division_1x1.csv 
Test Case 2 [2,2] – histogram_division_2x2.csv 
Test Case 3 [2,3] – histogram_division_3x3.csv 
Upon Execution of  the code a 1- Dimensional array of the type int64 

Question 3 
The Jupyter Notebook file(.ipynb format) that contains the code for 
the third question is kept in the ‘question 3’  folder. Upon execution a 
3X3 2- Dimensional numpy array with the data type ‘float64’ is 
displayed. The Jupyter Notebook environment displays the output 
immediately. 

Question 4 
The Jupyter Notebook file (.ipynb format) that contains the code for 
the forth question is kept in the ‘question 4’ folder. There is no 
specific output for this but shows the number of epochs run in the 
code and validation accuracy. The classification accuracy is obtained 
from the next question that is question 5. The weights calculated is in 
the same folder and the name of the file is ‘question 4 
weights_resnet(q4).pth’ 

Question 5 
The Jupyter Notebook file(.ipynb format) that contains the code for 
the fifth question is kept in the ‘question 5’  folder. Upon execution it 
displays the classification accuracy mentioned above in question 4. 
The weights calculated in question 4 is also added to the ‘question 5’ 
folder and name of the weights file is ‘question 4 
weights_resnet(q4).pth’ 

Question 6 
The Jupyter Notebook file(.ipynb format) that contains the code for 
the sixth question is kept in the ‘question 6’  folder. Upon execution it 
displays a confusion matrix resulting from the output  of question 5. 
Run the code in ‘question 6.ipynb’ file below the cell which has fifth 
question’s code in ‘question 5.ipynb’ file to get the confusion matrix 

Question 7 
The Jupyter Notebook file(.ipynb format) that contains the code for 
the seventh question is kept in the ‘question 7’  folder. The code for 
this was run on google colab pro with GPU. The model is explained 
below: 
The script is intended to train and validate a Faster R-CNN object 
detection model, which is intended to determine whether or not 
people are appropriately wearing masks in photos. It makes use of a 
pre-trained ResNet-50 backbone and refines it for three distinct 
categories that correspond to various mask-wearing conditions. The 
dataset, which is controlled by a unique Dataset class, is made up of 
pictures and the associated XML annotations for training and 
validation. The model predicts bounding boxes and labels after being 
trained using the Adam optimizer over several epochs. In order to 
assess the correctness of the model, validation is carried out after 
training by comparing the predicted counts of mask-wearing states 
with the ground truth obtained from XML annotations.
