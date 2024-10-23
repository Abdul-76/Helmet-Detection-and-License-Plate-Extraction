# Helmet-Detection-and-License-Plate-Extraction-using-YOLO-V3-and-Optical-Character-Technique

1. In first part the input is given as a video and is converted to frames and these frames are send for detection
2. Primarily, detection will happen at three levels using YOLOv3.
3. In the first level, we will detect the person and the vehicle that they are driving.
4. In the second level we will detect whether that person is wearing a helmet or not.
5. In the second level, if the person is not wearing their helmet, then in the last level, we will detect their registration plate and extract their registration plate number using Optical Character Recognition.
6. Only the objects that are detected will be extracted using Image AI library.
7. To detect the registration plate, we will have to train our model.
8. To train our model, we will create a bounding box around the object and extract the numbers into xml and json files.
9. The above step also involves image pre processing like rotating the image for increased accuracy.
10. Since this system takes a video input, speed will be of the essence, as we need to get our results almost instantaneously.
