# Add_Noises
Add all kinds of noise to a picture, including:

GrayscalePeppers\GaussianNoise\MeanfilterOnGauss\MeanfilterOnSnP
SaltandPepper\MedianfilterOnGauss\MedianfilterOnSnP\AdaptiveThresholding\Prewitt\Sobel

#Windows

To compile these codes, you need to install OpenCV, and configure them in your Visual Studio. Download OpenCV from officical web, make sure the version you downloaded. 
The steps are:
1. Add <OPENCV_PATH>\build\x64\vc12\bin to the environment path.
2. Add <OPENCV_PATH>\build\include, <OPENCV_PATH>\build\include\opencv and <OPENCV_PATH>\build\include\opencv2 to your VS including path. Right click the project and select Settings or Attributes, the including path is in VC++ path.
3. Add all files under <OPENCV_PATH>\build\x64\vc12\lib to your link inputs. That could be found in LINK -> INPUT. You can also separate the files into two parts by whether having suffix d, and add those files with suffix d into your DEBUG mode, add others into RELEASE mode.
