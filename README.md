# Neurowatch

BSc Computer Science, University of London Final Project implementation.

This consists on a surveillance camera system with a client that can run on a single board computer such as a raspberry pi and a server, both implemented in python.

* The client uses computer vision motion detection techniques: Background substraction and Three Frame Differencing to detect movement and a convolutional neural network model(YOLOv8) to detect objects.
  
* The server is implemented using Django and django-rest-framework and also features authentication, email and push notifications.

* An Android client is also planned.
