# Image Classification for a City Dog Show
![image](https://github.com/areegtarek/Use-a-Pre-trained-Image-Classifier-to-Identify-Dog-Breeds/assets/46351336/6cf6855e-9c3b-4f88-baa2-f21a3d62b92f)

## Project Goal
To improve your programming skills using Python by applying an image classifier to identify dog breeds.

## Project Description
You will use a pre-trained image classifier that can recognize over a thousand different objects, including different breeds of dogs. The classifier is based on a deep learning model called a convolutional neural network (CNN), which can learn features from images and use them to classify the images into categories.

You will use the classifier to help the organizing committee of a citywide dog show with contestant registration. Every participant that registers must submit an image of their dog along with some biographical information. The registration system automatically tags the images based on the biographical information, but some people may try to register pets that are not dogs. You need to verify that the images are indeed of dogs and not of other animals.

## Your Tasks
- Compare the performance of three different CNN architectures (AlexNet, VGG, and ResNet) on classifying images as "dogs" or "not dogs".
- Choose the best CNN architecture for your application and evaluate how well it can identify the breed of a dog from an image.
- Measure the time and computational resources required by each CNN architecture to process the images.
- Document your findings and explain your reasoning in a report.

## Important Notes
- You do not need to create the image classifier from scratch. It is already provided to you in the `classifier.py` file. You only need to use your Python skills to call the classifier function with different parameters and process the output.
- The `test_classifier.py` file contains an example program that shows how to use the classifier function. You can use it as a reference or a starting point for your own program.
- Some breeds of dogs look very similar and may be hard to distinguish even for humans. The classifier may not be able to correctly identify the breed of every dog image, especially if it has not seen many examples of that breed before. This is a limitation of the classifier and not a reflection of your skills.
- For more information and FAQs, please check [this link](https://www.udacity.com/course/ai-programming-python-nanodegree--nd089).
