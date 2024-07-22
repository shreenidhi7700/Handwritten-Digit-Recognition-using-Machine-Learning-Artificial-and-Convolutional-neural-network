# **Hand Written Digit Recognitioin using Machine Learning, Artificial and Convolutional Neural Networks**
Classify a given image of handwritten digit into one of the 10 classes representing integer values from 0 to 9 using Machine and Deep learning algorithms, and compare between various models and find the classifier that works best for our project.

## **Problems with handwritten digits**

The handwritten digits are not always of the same size, width, orientation and justified to margins as they differ from writing of person to
person, so the general problem would be while classifying the digits due to the similarity between digits such as 1 and 7, 5 and 6, 3 and 8, 2 and
5, 2 and 7, etc.

This problem is faced more when many people write a single digit with a variety of different handwritings. Lastly, the uniqueness and variety in the handwriting of different individuals also influence the formation and appearance of the digits.

Now we introduce the concepts and algorithms of deep learning and machine learning.

The provided Handwritten digits are images in the form of 28*28 gray scale intensities of images representing an image along with the first
column to be a label (0 to 9) for every image.

## **About the Project**
*  A digit recognition system is a type of technology that can automatically identify and classify numerical characters, typically from 0 to 9. These systems are most commonly used to interpret handwritten digits,
*   Digit recognition system is the working of a machine to train itself or recognizing the digits from different sources like emails, bank cheque,
papers, images, etc.

*   In different real-world scenarios for online handwriting recognition on computer tablets or system, recognize number
plates of vehicles, processing bank cheque amounts, numeric entries in forms filled up by hand (say — tax forms) and so on


*   Here's a breakdown of how digit recognition systems work:

**Data Preprocessing**: The system takes an image of a digit as input. This image is then preprocessed to ensure consistency. Preprocessing may involve steps like resizing the image, converting it to grayscale, and thinning lines.

**Feature Extraction**: Key characteristics of the digit image are extracted. These features could be things like the distribution of black pixels, the number of endpoints (ends of lines), or the overall shape of the digit.

**Classification**: The extracted features are fed into a machine learning model that has been trained to recognize digits. Common algorithms used for digit recognition include K-nearest neighbors and convolutional neural networks (CNNs). CNNs are particularly effective due to their ability to learn complex patterns from data.

**Output**: The model outputs the most likely digit based on the extracted features.
