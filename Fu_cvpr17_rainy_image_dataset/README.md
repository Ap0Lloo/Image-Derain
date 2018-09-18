
1)	This dataset offered by:
	[1] X. Fu, J. Huang, D. Zeng, Y. Huang, X. Ding and J. Paisley. ¡°Removing Rain from Single Images via a Deep Detail Network¡±, CVPR, 2017.
	[2] X. Fu, J. Huang, X. Ding, Y. Liao and J. Paisley. ¡°Clearing the Skies: A deep network architecture for single-image rain removal¡±, IEEE Transactions on Image Processing, vol. 26, no. 6, pp. 2944-2956, 2017.

	This dataset contains 1,000 clean images. Each clean image was used to generate 14 rainy images with different streak orientations and magnitudes.

	They use PhotoShop to generate rainy images: http://www.photoshopessentials.com/photo-effects/rain/


2)	We tested 100 synthetic rain images of the dataset, each testing its eighth rainy samples.
	All images are resized to 256*256 and the derain results are saved as color images.

	The rain removal results of all the methods listed in paper are saved in the derain_image directory.
	The numerical results of all methods are listed in the numerical_result directory.