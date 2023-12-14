!!!!  Made by Vita_Aeterna !!!!
©Used DataSet "https://www.microsoft.com/en-us/download/details.aspx?id=54765"




Simple tensorflow Neural Network with Sigmoid and Binary_Crossentropy, learning with and about accuracy and loss.
All of the Pictures are converted to (50,50) sized Pictures and also GrayScaled (To improve the learning process of the Neural Network).
At first i tested multiple Versions(different Dense layers, Conv layers and Layer size) of The Neural Network, The one with the best Accuracy and smallest Loss is used to predict the Animals.
I noticed that if u give an invalid picture like a Man or a Woman the Neural Network will always give the Ouput 0!





As Input a Picture of a Dog or a Cat is given (Need to change Name of your Picture in "EndProduct" script, default Name is "dog.jpg")
Note that the Picture has to be in png or jpg Format. 
Path of Cat and Dog Pictures (DataSet) in "ImageUsing" need to be changed too! (DATA_DIR)



As Output, 0 or 1 is given. 
0=Dog;
1=Cat;

All packages (pip) used in this Project:
  tensorflow / tensorflow-gpu
  pickle
  numpy
  random 
  os
  matplotlib
  tqdm
  cv2
  time
  
