# Fast-Fourier-Transform-and-High-Boost-Filtering-of-Satellite-Images

This is the course project of GNR 607 - Satellite Image Processing course of CSRE, IIT Bombay.

The project consist of 3 scripts written separately named fft.ipynb, logstretch.ipynb and high_boost_filter.ipynb.

## Codes

- fft.ipynb file consists of classes that calculate fast Fourier transform and shifting of magnitude plot to center of image.It also contain image reshape class which convert image to a (2n x 2m) size if image size is not in this format by adding dummy rows and columns.

- logstretch.ipynb file consist of class that do logarithmic stretch of magnitude plot so that magnitude plot visual is better and appealing.

- high_boost_filter.ipynb file consists of image reading cv2 library to read grayscale image, phase plot, magnitude plot, high boost filter class that defines boost coefficient and window size taken and finally taking inverse Fourier transform.

## Instructions

- Input the image, boost coefficient and window size in high_boost_filter.ipynb file. Change the image and values of boost coefficient and window size according to the required results.

- Run the high_boost_filter.ipynb file , it will take all class inputs from other 2 files and display normal magnitude plot, stretched magnitude plot, frequency plot and finally the output image.

- Compare input image with output by changing boost coefficient and window size.  

## Results

Tested in two types of images - satellite image and normal image

### Satellite Image

#### Input 

![input](https://github.com/Mainak21/Fast-Fourier-Transform-and-High-Boost-Filtering-of-Satellite-Images/blob/master/Inputs/satellite_input_grayscale.png)

#### Output

![output](https://github.com/Mainak21/Fast-Fourier-Transform-and-High-Boost-Filtering-of-Satellite-Images/blob/master/Result%201%20-%20Satellite%20Image/satellite_output.png)

### Normal Image

#### Input

![zelda](https://github.com/Mainak21/Fast-Fourier-Transform-and-High-Boost-Filtering-of-Satellite-Images/blob/master/Inputs/zelda.png)

#### Output

![ouput_zelda](https://github.com/Mainak21/Fast-Fourier-Transform-and-High-Boost-Filtering-of-Satellite-Images/blob/master/Result%202%20-%20Normal%20Image/zelda_output.png)
