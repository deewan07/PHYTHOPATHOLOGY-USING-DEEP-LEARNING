# PHYTHOPATHOLOGY-USING-DEEP-LEARNING

Just like human diseases, plant diseases are also evident since the earliest of times.
Fossil evidence proves that plant diseases have existed on earth over 250 million
years ago and continues to do so. There have been many famines and other economical
disasters because of various plant disease outbreaks. Some of the major plant
epidemics were late blight of potatoes in Ireland (1845–60), coffee rust in Sri Lanka
(1870s), Panama disease of bananas in Asia (1990s) and so on. These epidemics
result in major losses for the economy. In this paper we discuss a model using deep
learning which would help in getting to know regarding any harm a crop faces before
it is damaged completely. This is done by looking closely at a crop’s leaves and further
classifying them into categories for better understating of the health of the crop.
Here, the dataset is primarily for apple leaves only. Firstly, image preprocessing is
done followed by data augmentation. After training and testing of the model the
results are out which are then categorised into four classes mainly, healthy leaves,
scab, rust and multiple diseased leaves.

DenseNets is a common CNN-based ImageNet that is used by a range of applications
such as classification, segmentation, location, etc. For representational capacity,
most models before DenseNet relied solely on network depth. DenseNets maximize
the network’s ability by feature reuse instead of extracting representational power
from extremely deep or large architectures.

EfficientNet is another (newer) common CNN-based ImageNet model that in
2019 was able to perform SOTA in multiple image tasks. With considerably less
criteria, EfficientNet executes revolutionary model scale-up to achieve excellent precision.


Proposed Model
To make sure that the plant or crop is healthy, detection of infected leaves at an
early stage is crucial. This ensures that the farmer gets the harvest they deserve
without any hassle. Hence, in this paper we have used Deep Learning DenseNet
model for classification of the leaves. We have divided our model in a few steps.
Firstly we captured the image of the leaf and then performed image preprocessing.
Next, the preprocessed data is augmented by various techniques namely, flipping,
convolution and blurring to obtain an increased dataset. Further the edges of the
images were detected using the canny edge detection method. And once the model
is trained and tested we classify the leaves into four different categories. These
classifications are healthy leaves, scabbed leaves, leaves with rust and finally the
most infected leaves which are the unhealthy ones with multiple diseases.
