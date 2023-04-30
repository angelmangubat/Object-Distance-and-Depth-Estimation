# Object-Distance-and-Depth-Estimation
This project is used to process simulated video of urban traffic scene from IPG car maker. (1) Depth estimation which detects and object distance and generates depth map. (2) Object detection algorithm which identifies objects in front of the vehicle. (3) Distance estimation algorithm which predicts object distance from the vehicle.

This project was run and tested in Google Colab.

For the Depth Estimation:
  The model used came from Intel MiDas:
      Ranftl R, Lasinger K, Hafner D, Schindler K, Koltun V. Towards robust monocular depth estimation: Mixing datasets for zero-shot cross-dataset transfer. IEEE transactions on pattern analysis and machine intelligence. 2020 Aug 27;44(3):1623-37.
![image](https://user-images.githubusercontent.com/116680578/235370173-3a4bc703-8773-484e-813e-128199c636a5.png)


For Object Detection and Distance Estimation:
  The model used is YOLO v5
  Main algorithm reference came from:
    H. Ramadan. (2022). Vehicle Distance Estimation [Online]. Available: https://github.com/RmdanJr/vehicle-distance-estimation 
