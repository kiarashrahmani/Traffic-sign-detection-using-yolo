# Traffic-sign-detection-using-yolo  
Our project focuses on developing a traffic sign detection model using the YOLO framework. YOLO is renowned for its real-time object detection capabilities, making it an ideal choice for addressing the dynamic and time-sensitive nature of traffic environments. By training the model on an extensive dataset of annotated traffic sign images, we aim to equip it with the ability to accurately detect and classify  traffic signs commonly encountered on roads.

Within this project, we have harnessed the power of YOLO to proficiently detect a diverse set of 10 essential traffic signs.  
list of the traffic signs :

1.Stop   
2.No pedestrian crossing  
3.No parking  
4.Parking  
5.Give way  
6.One way  
7.No left turn  
8.Speed limit  
9.Bus lane  
10.Pedestrian crossing

# How to run:

1.Open Google colab in your browser  
2.Open the folder containing this folder  
3.Run Traffic_sign_detection.ipynb  

# Dataset
You can find our meticulously curated dataset in the dedicated "Dataset" folder within this repository. Our dataset boasts a comprehensive collection of 1027 meticulously labeled images for training purposes, alongside an additional 219 images reserved for validation purposes.
Each image within the dataset has been carefully and accurately labeled, ensuring that every traffic sign is precisely annotated. This dedication to precision empowers our dataset to serve as a reliable foundation for training and validating our traffic sign detection model.
Your engagement with the dataset is integral to contributing to the development of accurate and efficient traffic sign detection capabilities. Should you have any inquiries or require further information about our dataset, please don't hesitate to reach out.  
# Accuracy 
YOLOv5s summary: 157 layers, 7037095 parameters, 0 gradients, 15.8 GFLOPs
                 Class     Images  Instances          P          R      mAP50   mAP50-95: 100%|██████████| 55/55 [00:04<00:00, 13.17it/s]
                   all        219        288      0.914      0.917      0.943      0.689
                  Stop        219         41      0.974      0.912      0.939      0.818
No pedestrian crossing        219         27      0.904          1      0.994      0.898
            No parking        219         20      0.907      0.971      0.963      0.841
               Parking        219         25      0.983       0.96      0.974      0.795
              Give way        219         21      0.977      0.952      0.989      0.802
               One way        219         70      0.936      0.838      0.957      0.566
          No turn left        219         22      0.663      0.727       0.72      0.433
           Speed limit        219         21          1       0.81      0.993       0.56
              Bus lane        219         20      0.952      0.998      0.988      0.707
   Pedestrian crossing        219         21      0.849          1      0.918      0.472
