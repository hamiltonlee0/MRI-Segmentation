The project is on jupyter notebook. Are two jupyter notebooks in this project.
The one titled MRI_Segmentation is the complete segmentation pipline for Mid-Coronal Slices.
The other notebook is an attempt as using transformations on volumes instead of slices.
This was not successful for me as my computer is not powerful enough to run the registration
algorithms on volumetric data with a sufficeint amount of steps to reach alignment. 
In theory the same concepts applied to the slices should work on volumes as well.

Several libraries are needed:

os
numpy
scipy
nibabel
imageio
matplotlib
Pillow
Scikit-image
pandas
openCV
simpleITK

Make sure the *.npy files are in the same folder as the jupyter notebook. They contain
the necessary training, validation, testing data etc...
