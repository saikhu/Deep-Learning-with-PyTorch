## Chapter # 2 Pretrained networks

This chapter covers
- Running pretrained image-recognition models
- An introduction to GANs and CycleGAN
- Captioning models that can produce text descriptions of images
- Sharing models through Torch Hub



#### 2.1 A pretrained network that recognizes the subject of an image

The pretrained network we’ll explore here was trained on a subset of the ImageNet dataset http://imagenet.stanford.edu. ImageNet is a very large dataset of over 14 million images maintained by Stanford University. ImageNet Large Scale Visual Recognition Challange (ILSVRC). The training set for ILSVRC consists of 1.2 million images labeled with one of 1,000 nouns (for example, “dog”)

The dataset can be used for the following tasks:
- Image Classification (telling what object categories the image contains)
- Object Locallization (identifying objects’ position in images)
- Object Detection (identifying and labeling objects in images)
- Scene Classification (classifying a situation in an image)
- Scene Parsing (segmenting an image into regions associated with semantic categories, such as cow, house, cheese, hat)