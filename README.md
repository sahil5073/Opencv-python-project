# List of openCV python projects in this repo
# 1. Cartoonization
To use the code locally, you'll firstly need to have Python v3 installed. You can download it from [https://www.python.org/downloads/], if it isn't already in your system.

Then, you'll need to run the following command to ensure that all the related dependencies are configured into your system.

     python -m pip install pyttsx3 speech_recognition wikipedia smtplib googletrans difflib

**NOTE**: In Ubuntu and Mac OS, use `python3` instead of `python`, if both _Python 2_ as well as _Python 3_ have come installed in your system.

  Packages for standard desktop environments (Windows, macOS, almost any GNU/Linux distribution)
   - Option 1 - Main modules package: pip install opencv-python
   - Option 2 - Full package (contains both main modules and contrib/extra modules): pip install opencv-contrib-python
   
 Import the package:
    -import cv2

      All packages contain haarcascade files. cv2.data.haarcascades can be used as a shortcut to the data folder. For example:
      cv2.CascadeClassifier(cv2.data.haarcascades + "haarcascade_frontalface_default.xml")

Then, you can simply execute the script using any Python interpreter, or by using the following command into your terminal: 

     python "cartoonization.py"

  
