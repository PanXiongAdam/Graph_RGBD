Title: Graph-based RGB-D Image Segmentation Using Color-directional-region Merging

If you use this method in your research please cite the Paper:
   [1] X. Pan, Z. Zhang, Y. Liu, C. Yang, Q. Chen, L. Cheng, J. Lin, and R. Chen, "Graph-based RGB-D Image Segmentation Using Color-directional-region Merging," in 2019 IEEE International Conference on Acoustics, Speech and Signal Processing (ICASSP), May 2019, pp.2417-2421.

Setup:
   If you want to run the algorithm, you should do:
      1. create the folder of image, 'images' is the folder's name
      2. create the folder of normal, 'normal' is the folder's name
      3. the extension of data must be '.mat', and the name of the variable is 'normal' in the normal data
      4. the extension of data must be '.mat', and the name of the variable is 'image' in the image data


  the paramter denotes:
     varepsilon: the threshold value T in the equation (6)
     sigma      :  the paramter of bi-semi-gaussian
     beta        :  the variable of v in the equation (4)

Note: if it isn't running, you should set the System environment with python and install cycler,numpy,opencv,scikit_image,scipy and pillow. My python version is 3.6
