# Digit Recognizer

Welcome to my solution to the Hello World of Computer Vision.

I took several approches to the MNIST dataset problem and copied the files for those runs.

- Digi Recognizer.ipynb
  - This approch is a simple KNN classifier from Scikit Learn While 
  - Best score I was able to get with this was about 96.500%
- Digit Recognizer - CNN.ipynb
  - A very simple CNN scored 99.114%
- Digit Recognizer - CNN LDS.ipynb
  - This run involved a larger data set that I created by augmenting the MNIST data set
  - While there are more effecent ways to create this data I wanted to play around with python a bit so did things a bit more manurally
  - Scored 99.585%
- Digit Recognizer - CNN LDS LR.ipynb
  - This made some modifications to the network and changed from 30 epochs to 100
  - Scored 99.628%

  The neral networks were ran on a Vega Frontier Edition GPU using Metal by making use of PlaidML and Keras

  Datasets used can be downloaded [here](https://mega.nz/#!3PRARAoR!8gpu5z5O8dGjhuY9LzVYMjVwM-auzwJfvjH0I6PR33Q)
