# Face_mask_detection_using_live_vide_streaming(Finalproject)

## Abstract

COVID-19 pandemic is the most life-changing event. With the reopening of countries from the lockdown, 
it is recommended to wear masks to prevent spread of virus. A survey shows that only 44% of people are
wearing masks. Our project makes the process of checking face mask on a person fast and efficient. It 
can be deployed in offices, schools, college. In our project we are using CNN based MobileNetV2 Architecture
for Mask Detector Model. In our project we are using CNN based MobileNetV2 Architecture, OpenCV, Haar
Face Detector, Facenet and Face Recognition Library.





## Algorithms used:
### Mask Detection: 
In our project we are using CNN based MobileNetV2 Architecture for Mask Detector Model.
For live streaming as well as capturing of faces we are using OpenCV along with Haar Face Detector. 

### Face Recognition:
For Face Recognition model, we are using FaceRecognition library to extract encodings 
of captured faces and FaceNet model to compute the similarity between faces. For live streaming as well 
as capturing of faces we are using OpenCV along with Haar Face Detector. 



## Experimental sets:
The dataset for mask detection model is taken from Kaggle. The collected data is labelled into two groups;
with and without mask. The with_mask folder consists of 1915 images and the without mask folder consists of 1918 images.

The dataset for face recognition model has images of 37 persons, one image of each person. The collected
data is labelled by a unique identification number such as PID.





## Conclusion and future scope:
Here, we have discussed the project and implementation of Face Mask Detection System. Using face mask
detection system we can find out the people not wearing masks. These people can then be recognized via
face recognition system. Once the person is recognized he can be warned using the alert system via mail.
If someone is caught doing the same mistake more than five times he/she will be fined.
In near future the threat of virus will end and the rule of wearing masks will be withdrawn but there
are still various fields where wearing masks is important, virus or not. Surgeons, people working at 
pathology labs, research labs, mines and many manufacturing units and industries will still be required 
to wear masks. So this system can be used at such places to check if people working there are following
the norms or not.







