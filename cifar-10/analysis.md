# Overall analysis
Comparison between the FCN vs CNN model shows that the CNN is clearly superior in image classification.  
The CNN model achieved an accuracy of 70% while the FCN model only achieved an accuracy of 50%.  
The examples images being outside of the entire training set and containing an image that doesn't belong to any of the classes in the training set made an for an interesting evaluation.  
  
Interestingly, the FCN model was more decisive in its predictions, with a higher confidence level for the predicted class, while the CNN model was more uncertain in its predictions in some images. 
This FCN model was extremely confident that an ostrich was a horse, but the CNN model was more certain that it was a bird than a horse.