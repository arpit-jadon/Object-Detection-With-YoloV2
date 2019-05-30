# Object-detection-with-yolov2-and-corresponding-parameter-storing-in-csv-file
> This code is primarily for direct object detection in multiple images stored in a particular folder. Moreover, various parameters (like coordinates of detected object, confidence in the object detection, detected label, etc.) are also stored in a csv file where each row correspond to the parameters of all detected objects in a particular image.
>> simple procedure to detect objects in multiple images with this code is:
-Store all the images requiring object detection in the folder corresponding to input path. Run the code and the output images with detected objects highlighted by bounding boxes and text labels will be stored in the folder corresponding to the output path. Moreover, the parameters for each detected object in corresponding image can be found in the csv file saved in the mentioned directory. 

-Weights file for yolov2 can be downloaded from this link: (https://drive.google.com/drive/folders/0B1tW_VtY7onidEwyQ2FtQVplWEU). Also, place the file in the 'bin' folder. If no such folder exist then create one and store the weights file into it. I used the weights named yolo.weights

This work is inspired by this yolov2 darkflow implementation (https://github.com/deep-diver/Object-Detection-YOLOv2-Darkflow).
Note that this code is for direct prediction from multiple raw images using pre-trained yolov2 weights and then storage of the parameters in a csv file.
