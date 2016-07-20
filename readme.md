## Hey Waldo: labeled images of the Where's Waldo puzzle

This repository contians labeled images of the Where's Waldo puzzle for use in classification and image recognition problems. Along with the labeled images, included are 19 original images, as well as the Python script used to create the smaller labeled images. Color, grayscale, and black or white versions of the labeled images are included in this repository. 

### formats
- 256 x 256 pixels (317 images)
- 128 x 128 pixels (1344 images)
- 64 x 64 pixels (5376 images)

### discussion

I decided to label images as containing Waldo regardless of where Waldo is located in the image. As such, there are images that are labeled as Waldo that are not strictly part of the puzzle. Waldo look-alikes, such as those with different hair styles or glasses, were also labeled as Waldo. This was just due to the way in which I decided to approach the problem, so feel free to relabel the images according to your needs and interpretation. 

Classification with these images is a difficult problem due to the Waldo's variable size (scaling issue), repeating patterns (red/white stripes present on other objects), occlusion (Waldo is often blocked by other people or objects), and the nature of the data, which is unbalanced (most images do not contain Waldo). Nevertheless, it's a fun application and I invite others to give it a try and share their results. 
