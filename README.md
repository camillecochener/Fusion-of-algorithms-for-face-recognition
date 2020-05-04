<div align='center'><h2>Challenge Large Scale Machine Learning</h2></div>

<div align='center'><h3>Theme: fusion of algorithms for face recognition</div>

<div align='justify'>Facial recognition is the process of identifying or verifying the identity of a person using their face. Today, it’s considered to be the most natural of all biometric measurements. Biometric means identity verification of persons according to their physical and behavioral characteristics. In the case of facial biometrics, a sensor captures a face, then transforms it into a vector of features and compares this transformed image to those held in a database. The biometric system confirms the correct match.
The increasingly ubiquitous presence of biometric solutions and face recognition in particular in everyday life requires their adaptation for practical scenario. In the presence of several possible solutions, and if global decisions are to be made, each such single solution can be far less efficient than tailoring them to the complexity of an image.</div>
<br>
  
**Objective**
The goal was to build a fusion of algorithms in order to construct the best suited solution for comparison of a pair of images. This fusion will be driven by qualities computed on each image.

**The data**

The data are from IDEMIA databases. 

The training set includes 9.800.713 observations and 37 variables explicatives. 

The variables are as follows:

* 13 variables relating to the quality of the second image (qr1 to qr13)
* 11 matching scores between the two images (s1 to s11)

<div align='justify'>The match score is a measure of similarity between the first and second biometric feature vectors. When match scores output by different biometric matchers are consolidated in order to arrive at a final recognition decision, fusion is said to be done at the match score level.</div>

The test set includes 3.768.311 predicted observations which is one-third of the training set.
