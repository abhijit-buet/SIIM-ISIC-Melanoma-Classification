# SIIM-ISIC-Melanoma-Classification 2020

This task required to predict from a patient's dermoscopic data whether that region is a malignant or benign.
The train set contrains about 33,128 patient's dermoscopic information including images, age, sex, location of the image and so on.

<h1> Proposed Method
  <h6>
  The train set contains both images and meta-data from the patients.
  To extract the images features, we have used efficientNet. Then, we concatenated both image features and meta-data features and pass   them through several fully-connected layer.
 The final layer predicts, whether that dermoscopic region is benign or malignant.

<img src="https://github.com/abhijit-buet/Images/blob/main/Slide4.PNG" width = "512" height = "328">


<h1> Result
  <h6>
    
    
 The evaluation was done using area under ROC. I have got a score of 0.862 which is top 20% in the leader board.
