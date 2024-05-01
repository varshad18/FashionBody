# FashionBody
FashionBody is a proof-of-concept system that uses computer vision and machine learning to perform a detailed analysis of the user’s body in terms of “fashion body shape”. This innovative system can detect the individual body parts such as arms, upper arms, shoulders, chest, waist, hips, thighs (legs breadth), and legs. On detection of these individual body parts, they are then passed onto a regression-based model to obtain a breakdown of the proportions of the user's body in terms of fashion. Various architectures and parameters were used to try and experiment with different models and the best one was opted to test.  A dataset was curated for the training and testing of FashionBody.

This is the repository for the python Tensorflow based Colabs for training the the two models of Fashion Body: Body Part Detection and Regression Models

![FashionBody_Capstone](https://github.com/varshad18/FashionBody/assets/42490142/8c957834-5e47-4c1f-b321-78096d6d3074)


## DIRECTORIES

| Name | Usage |
------------
| DataPreprocessing-BodyPartDetection | Colab code for preparing data for the Body Part Detection Model |
| DataPreprocessing-Regression | Colab code for preparing data for the Regression Model |
| BodyPartDetection | Colab code for building, training and testing the Body Part Detection Model |
| Regression | Colab code for building, training and testing the Regression model |
