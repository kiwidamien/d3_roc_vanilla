# Explaining ROC curves

This project uses a D3 visualization to illustrate what a [receiver operator characteristic](https://en.wikipedia.org/wiki/Receiver_operating_characteristic) (ROC) curve shows.

A deliberate choice was made to use credit scores as the "score" for the ROC curve, rather than the probability. Because many models use the ROC curve with the probability from ML models, there can be a misconception that the ROC curve is tied to this probability in some way. Here I am showing a (non-probability) score that we are thresholding for contrast.

There is a link to probability, namely:

Area under the Curve = Probability randomly chosen actual postive example has a higher score than a randomly chosen negative example

## Publishing

This will be presented as part of a blog post explaining ROC curves. A slightly nicer version using React + D3 is available [here](https://kiwidamien.github.io/d3_roc/), but it is harder to embed in a blog post.

## How to publish a D3 project

Go to **Settings** -> **Github Pages** -> **Source** -> **Master Branch**
