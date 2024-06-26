# Analysis

## Finding the loss function
The loss function being utilised in the default loss function that is set when creating a learner variable. This function is FlattenedLoss of the CrossEntropyLoss function. This function computs the cross entry loss between inputs and the targets

## Creating a T-SNE plot
A T-SNE plot was constructed utilised the get_preds() function once the AI of the learn object had processed the training image data set. This function returned an array probabilities of an image in the target set as well as another array that contained what the image should actually be classed as. This plot shows how clearly the AI can distinguish between different image topics.

![Image of T-SNE](/images/SNE.png)

## Creating an observation matrix
An observation matrix was created using the inbuilt classification Interpretation function in fast ai. An observation matrix displays what the AI has classed it predicated images as and then what the images are suppose to be class as.

![Image of Observation Matrix](/images/observation.png)
