# Gender-Identification
The model has been built using Principal Component Analysis and Support Vector Machines.

It identifies males and females with an accuracy of **80.5%**.

The 'models' file contains all the **'.npz'** and **'.pickle'** files obtained after data preprocessing and training.
The image **'PCA_trials'** shows a graph (No. of components vs Explained Variance Ratio) owing to which we have chosen 50 components as the Explained variance ratio is around 80 to 85% at that point as X co-ordinate.


In order to run the project
1) Make Sure all the files are in one single folder.
2) Open the integration_with_model file and provide the input image along with the image mode ('RGB' or'BGR') as  parameters to the integrate function.
