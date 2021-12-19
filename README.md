# AI Based Garbage Classification

This project uses [TensorFlow Lite IoT Image Classifier](https://github.com/androidthings/sample-tensorflow-imageclassifier) with custom trained image classifier in order to determine the garbage belongs to which class. You can train your custom classifier as described [Recognize Flowers with TensorFlow Lite on Android](https://codelabs.developers.google.com/codelabs/recognize-flowers-with-tensorflow-on-android/#0). 

## How the system works
1. It takes a shot of garbage
2. Pass it to the classifier.
3. Classifier makes a decision about it fits which category(paper, metal or plastic more
4. Turn on the LED of the decided category
5. Other systems are able to use this decision for performing some actions. For example, the system can open the lid of the section which is related to this decision in order to let the garbage down to this section.

> Note: Project was tested on Raspberry Pi 3.