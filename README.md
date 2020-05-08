# Social Distance Tracker
Detect if people are maintaining social distance.

Using pretrained YOLO model on COCO dataset.

This model has several advantages over classifier-based systems. It looks at the whole image at test time so its predictions are informed by global context in the image. It also makes predictions with a single network evaluation unlike systems like R-CNN which require thousands for a single image. This makes it extremely fast, more than 1000x faster than R-CNN and 100x faster than Fast R-CNN.


Get weights from here https://pjreddie.com/darknet/yolo/

Run script.py

Input image
![Input image](https://github.com/anishajain22/SocialDistanceTracker/blob/master/image.jpg)

Output image
![Output image](https://github.com/anishajain22/SocialDistanceTracker/blob/master/output.jpg)

PS The depth isn't taken into account here. 
