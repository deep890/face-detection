# face-detection
hey there, in this i'm training the computer to check the faces of the images
we are importing 4 files : face_recognition, cv2, os and cv2_imshow.
I used google colab to run the code.
in read_img function, we are making a variable img. this img variable is resizing all the loaded images ( known images) 
make sure that you have viewed the loading_images_known.py and loading_images_unknown.py as what these files are that in the known file we are importing images of Elon musk, bill gates, and Obama
in the unknown file we have the same pictures of 2 above people and 1 is not from the known file.
we will train the computer to check that is there any photo from the known file in the unknown file. 
the computer checks every pixel from the known file into the unknown file and also draws a box on the face which means it has recognized the faces in the images
