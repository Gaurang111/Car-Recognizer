# Car-Recognizer
Stanford Cars Dataset 16,185 images and 196 classes of all the cars.

Overview:
  The Cars dataset contains 16,185 images of 196 classes of cars. 
  The data is split into 8,144 training images and 8,041 testing images, where each class has been split roughly in a 50-50 split. 
  Classes are typically at the level of Make, Model, Year, e.g. 2012 Tesla Model S or 2012 BMW M3 coupe.

Link to the Dataset:
https://ai.stanford.edu/~jkrause/cars/car_dataset.html



I've tried to used Transfer learning with :
VGG16, InceptionV3, EfficientNetB0, and MobileNetV2

Out of all the above models, MobileNetV2 gave descent accuarcy (60% test accuracy).
due to slow processor and limited GPU usage time in Colab, I've trained models without tuning and experimentation.
But, One could use different model or use fine-tuning to get better accuracy.


