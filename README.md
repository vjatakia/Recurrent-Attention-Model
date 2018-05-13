# Recurrent-Attention-Model
The Recurrent Attention Model (RAM) is a deep model that predicts the label of an image that is cluttered with bits from other images (noisy image) and predict the original image using the label. It has drawn inspiration from the Google's Visual Attention Model in 2014. The scope of the project is expanded to use this model on colored images and use the Inception Net model for feature extraction. 

A comparison to the baselines of Fully-connected and CNN was done to justify the performance of the RAM model. Different variations of the MNIST and CIFAR10 datasets including the cluttered images was fed into the RAM model and the output was recorded. The results from the experiments and the components of the model are better explained in the Project report titled RAM_report in the files section. 

File explanations: 
1. Baselines are the simple Fully-connected and CNN models used for comparison with the RAM model. 
2. MNIST Shifted Input.pynb includes the Translated and cluttered version of the MNIST dataset that is used as input for the RAM model. 
3. cifar10_cluttering.ipynb includes the Cluttered version of the cifar10 dataset that is used as input to the RAM model. 
4. color_flat_likelihood includes the colored and flattened version of the CIFAR10 dataset and using Maximum Likelihood Estimation for classification. 
4. color_likelihood includes the colored images in their original shape and using Maximum Likelihood Estimation for classification. 
5. gray_likelihood includes the grayscaled images in their original shape and using Maximum Likelihood Estimation for classification.  
6. RAM_report.pdf includes the detailed explanation for the model and the results from the experiments using the above stated models. 

