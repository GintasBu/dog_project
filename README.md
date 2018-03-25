# Dog breed recognizer

## What is all about

* Built an algorithm to identify canine breed given an image of a dog. 
* If given image of a human, the algorithm identifies a resembling dog breed. 
* 133 dog breeds were considered.

## Deep Learning models for dog breed recognizer

Trained two different deep learning models: one designed from scratch and another using transfer learning from Xception model with pre-trained coefficients. The accuracy of the test set was 85.6% for the transfer learning approach.

## Deep Learning models for partially covered face recognizer

An additional DL model was designed and trained to recognize humans and dogs when the image was partially covered. The idea was to build a recognizer, when a face in the image was partially covered (hat, scarf, etc). To generate data, I modified existing human and dog images by superimposing a black circle on the image with a random radius at random location. The trained model detected 100 out of 100 human images, and had only one false classification in dog images on the test sets.

# Contributions

This was a learning project, not a development. 

# License

This was a part of Coursera course, act accordingly. Reminding: plagiarism not recommended. But look and learn if find it useful.  
