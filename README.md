# ImageResize
<h1>Python Image Resizer</h1>

By NTech
28-04-2020

Requirements (covered in installation):
Python 3.X (Any Python 3)
pip
Pillow
glob

Installation:
1. Make sure you have python 3.X installed.
(Any version of Python 3)
2. Make sure you have pip installed.
https://www.liquidweb.com/kb/install-pip-windows/
3. Run in command prompt to install the packages:
pip install pillow glob3

Usage:
1. Put all images you want to be resized in "Images" folder in ImageResize (images must be compatible file types)
2. Make sure that the "Finished" folder in ImageResize is empty.
3. Navigate command prompt to ImageResize folder using "cd" command
4. Run "python resizer.py" in the command prompt.
5. Enter image width and height when the command prompt window asks.
6. Enter your desired finished image format (must be compatible file type)
7. Wait until the command prompt reads "100.0%", resized images will be in "Finished"

Compatible File Types for Input Images:
.bmp, .gif, .ico, .jpeg, .jpg, .png, .tiff

Compatible File Types for Output Images:
.bmp, .gif, .png, .tiff
