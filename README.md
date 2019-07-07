# undistort-images
We took a checkerboard with the square dimensions of 315mm and took several photos in order to cover the whole space, we then gave our code these images as inputs and ran our algorithm, as some of the images we took were blurry because of motion blur and shake because of the camera movement not all of the images were able to be calibrated so we used only some of the inputs. The next step was to detect the checkerboard pattern in our images Then we Read the first image to obtain image size Later on we generated world coordinates of the corners of the squares, as we already know that each square size in millimeters is 315mm We then calibrate the camera and go over the reprojection errors to make sure our error is not too big, We then visualize pattern locations and display parameter estimation errors The final step is to export the distortion parameters and with that data and the calibration data we can remove effects of lens distortion.