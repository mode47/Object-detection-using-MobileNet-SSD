# Object-detection-using-MobileNet-SSD
We will be using MobileNet-SSD network to detect objects such as cats, dogs, and cars in a photo. A combination of MobileNet and SSD gives outstanding results in terms of accuracy and speed in object detection activities.
# What is Object Detection?
Object detection is a computer technology related to computer vision and image processing that deals with detecting instances of semantic objects of a certain class (such as humans, buildings, or cars) in digital images and videos. Well-researched domains of object detection include face detection and Pedestrian Detection. Object detection has applications in many areas of computer vision, including image retrieval and video surveillance.

Object detection as the term suggest is the procedure to detect the objects in real world. For example, dog,car,humans, birds etc. In this process we can detect the presence of any still object with much ease. another great thing that can be done with it is that detection of multiple objects in a single frame can be done easily. For Example, in the image below the SSD model has detected mobile phone, laptop, coffee, glasses in a single shot. It detects different objects in a single shot.

# SSD MobileNet Architecture
The SSD architecture is a single convolution network that learns to predict bounding box locations and classify these locations in one pass. Hence, SSD can be trained end-to-end. The SSD network consists of base architecture (MobileNet in this case) followed by several convolution layers:

