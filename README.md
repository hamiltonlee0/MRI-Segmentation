# MRI-Segmentation
Registration Based Segmentation for MRI Mid-Coronal Slices (specifically for the cerebral cortex and cerebral white matter regions of the brain).
<br>
To read full Project report look at the PDF file (Report_MRI.PDF). This contains a detailed documentation on attempted methods and relevant mathematics.
<br>
The main project code with all attempts is located in (Project Files > MRI_Segmentation.ipynb). These attempts focused on 2D pixel images to attempt registration by assuming the middle index of all volumes along the coronal index were in fact the middle coronal slice. VolumetricReg.ipynb was an attempt focused on 3D voxel volumes applying the same techniques for alignment. The machine used to test this was not powerful enough to reasonably run the code with the desired learning rates and steps to achieve acceptable alignment.
