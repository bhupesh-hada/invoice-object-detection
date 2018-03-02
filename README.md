# invoice object detection
* A model has been trained on a number of computer generated and handwritten invoice pictures in order to detect the filled values and the unfilled values in an invoice. 
* values could be any name(alphabatic) or a number in an invoice 
* https://imgur.com/a/cX1Rh (what we actually want)




# what has been done
1. Collected a few handwritten and computer generated invoice pictures
2. Classifying the objects in an image using Labelimage which draws boxes around an object and creates an XML file which descrbes the objects in an image
3. Split this data into train/test samples
4. Generate  tfrecords from these splits
5. Setup a .config file for the model of choice 
6. Train the model
7. Export graph from new trained model
8. Detect custom objects in real time!

* the model here used is pretrained but it has been trained on the collected invoice images  ssd_mobilenet_v1_coco_11_06_2017


## Drawbacks
1. the images here used for training are not much
2. I have used the tensorflow for CPU which affects the processing speed  


