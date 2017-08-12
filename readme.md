# Hey Waldo

[![License](https://img.shields.io/badge/License-ODbL%201.0-blue.svg)](https://opendatacommons.org/licenses/odbl/1.0/)

This repository contains labeled images of the Where's Waldo puzzle for use in 
classification and image recognition problems, which I painstakingly hand labeled. 
Along with the labeled images are 19 original images, as well as the Python script 
used to create the smaller labeled images. Color, grayscale, and black or white 
versions of the labeled images are included as part of the data set. 

### Image Formats
- 256 x 256 pixels (317 images)
- 128 x 128 pixels (1344 images)
- 64 x 64 pixels (5376 images)

### Discussion

I decided to label images as containing Waldo regardless of where Waldo is located 
in the image. As such, there are images that are labeled as Waldo that are 
not strictly part of the puzzle. Waldo look-alikes, such as those with different
hair styles or glasses, were also labeled as Waldo. This was just due to the way 
in which I decided to approach the problem, so feel free to relabel the images 
according to your needs and interpretation. 

Classification with these images is a difficult problem due to the Waldo's variable
size (scaling issue), repeating patterns (red/white stripes present on other objects),
occlusion (Waldo is often blocked by other people or objects), and the nature of the
data, which is unbalanced (most images do not contain Waldo). It's a tough but 
fun application and I invite others to give it a try and share their results. 

### Fun Stuff

- Playing Where's Waldo Using a Tiramisu Network for Semantic Segmentation
    - [Article](https://hackernoon.com/wheres-waldo-terminator-edition-8b3bd0805741)
    - [Github Repository](https://github.com/bckenstler/TheresWaldo)

