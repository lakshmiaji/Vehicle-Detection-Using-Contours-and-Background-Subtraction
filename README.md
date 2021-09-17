# Vehicle-Detection-Using-Contours-and-Background-Subtraction
Detecting vehicles from traffic videos using the basic background subtraction and contour detection with OpenCV library.

Background subtraction is a mainstream algorithm for moving object detection in video surveillance systems.
The base in this approach is that of detecting moving objects from the difference between the current frame and reference frame, which is often called ‘Background Image’ or ‘Background Model.
Here I used OpenCV libraries cv.BackgroundSubtractorMOG2. to generate the foreground mask.

After foreground detection, using cv2.findContours detect contours.








References

Thanks to Taha Anwar https://bleedai.com/video-contour-detection-101-the-basics-pt1-2-2-2/
 
