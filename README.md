# Dog_Breed_Classification
This Dog Breed classification Project allowed me to venture a lot of possible available pretrained networks and use them to get a better classification of the images that i personally had.
With the help of CNN i was also able to create a network from scratch that would allow me to classify the dog breeds with a relatively really low accuracy than the one, we got from the transfer learning network.
I have managed to use some of the pretrained networks to:
* First: Identify wheather the images that we are lookin into is a of a dog or a human or something else.(These are called as detectors in the notebook)
* Second: After the images are detected as dogs we use a predictor function that in turn uses either my own network that I created from scratch or the one that uses transfer learning to predict the dog breed for that image. Incase it is a human image then we again use the predictor function to give a prediction of the dog breed that the human resembles to. If the image is detected as neither than we throw an error message!
* Third: We used multiple techniques and numerous ways to augment our data, play with the classifying network as well as with the network from scratch and also with different types of optimizers and optimization techniques to end up with the resultant notebook that we present here to have the highest result as per out research.

I hope the project helps. Enjoy!

