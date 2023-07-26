<p>
Earlier we used traditional methods(canny edge and Hough Transform) for the lane detections but it was not a good option for complex curves , shadows, varying colors on road, bad weather conditions.
Then we extended our approach to use Deep Learning models and tried different CNN models for single Lane detection,, we got satisfying results but due to limitations like multiple lanes were not detected, occlusions
due to vehicles and pedestrians were affecting lane detection so we extended our approach to models which can give good results for multiple lane detection and use the global context information to infer the vacancy or 
occluded part . By using YOLOP we tried <strong> multiple lane detection, drivable area </strong> although object detection is not part of our project </p>
