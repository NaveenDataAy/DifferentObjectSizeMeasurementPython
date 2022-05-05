# object_size_measurement
Python used to measure the size of objects in an image.
load our image from disk, convert it to grayscale, and then smooth it using a Gaussian filter.
compute the Euclidean distance between the our sets of midpoints
compute the dimensions of the object (in inches) by dividing the respective Euclidean distances 
