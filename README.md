# invoice object detection
A model has been trained on a number of computer generated and handwritten invoice pictures in order to detect the filled values and the unfilled values in an invoice 
values could be any name(alphabatic) or a number in an invoice 



# what has been done
Collected a few handwritten and computer generated invoice pictures
Classifying the the objects in an image using Labelimage which draws boxes around an object and creates an XML file which descrbes the objects in an image
Split this data into train/test samples
Generate  tfrecords from these splits
Setup a .config file for the model of choice 
Train the model
Export graph from new trained model
Detect custom objects in real time!




