# Handwritten Number Recognition with Pattern Recognition

Image recognition is referred to us the ability to recognize certain people, animals, objects or other targeted subjects through the use of algorithms and machine learning concepts. The term “image recognition” is linked to “computer vision,” which is an overarching label for the process of training computers to “see” like humans, and “image processing,” which is a catch-all term for computers doing intensive work on image data, however pattern recognition is the automated recognition of patterns and regularities found in data.

Pattern recognition is used to give human recognition intelligence to machine which is re- quired in image processing. Pattern recognition is used to extract meaningful features from given image/video samples and is used in computer vision for various applications like biological, biomed- ical imaging or plate number recognition. In my project, i am going to explore using the same technique for detecting number in an image. 

Stages of Experiment: 
![alt text](https://github.com/FrankDidier/HNRS_PR-Number-Recognition/blob/master/ter.png "Stages of Experiment")

In this project, I’ll use numbers, but this could translate to all letters of the alphabet, words, faces etc...

## Test Output

Output from an input from of an image containing number 8: 
![alt text](https://github.com/FrankDidier/HNRS_PR-Number-Recognition/blob/master/A.jpeg "Output from an input from of an image containing number 8")

Performed on other numbers digit: 
![alt text](https://github.com/FrankDidier/HNRS_PR-Number-Recognition/blob/master/result.jpeg "Results:performed on other number digit")

## Getting Started

These instructions will get you a copy of the project up and running on your local machine for development and testing purposes. See deployment for notes on how to deploy the project on your local machine.

### Prerequisites

Download and install Python 3.x
Install Matplotlib Library.
It is a plotting library for python and it’s numerical mathematics extension Numpy.

```
sudo pip install matplotlib
```
Install Numpy Library.
It is a library for python which adds a support for large, multi-dimensional arrays and matrices, along with a large collection of high-level mathematical functions to operate on these given arrays.

```
sudo pip install numpy
```
Install Pillow/PIL Library.
It is a python image library which support opening ,manipulating as well as saving many different image file formats.

```
sudo pip install PIL or sudo pip install pillow
```

## Running the tests

How to run the tests for this system

### Running and testing using an existing an test image

Test image directory: ”images/test.png”

```
python TestingFile.py
```
You can also run it in Python 2 after debugging out differences.

```
python2 TestingFile.py
```

### Running and testing using your own test image

To test using different images: 
Go to images folder, add your image and modify the file name on the last line (77th) of the source code file named ”TestingFile.py”.

```
77 whatNumIsThis('images/xxxx.png')
```
And then re-run the above command.


## Contributing

Please contact me for details on my code of conduct, and the process for submitting pull requests to me.


## Author

* **ISINGIZWE Didier Frank** - [HNRS_PR-Number-Recognition](https://github.com/HNRS_PR-Number-Recognition)
