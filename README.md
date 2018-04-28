# walking_jogging_classifier

Logistic regression classifier using SKlearn is used to Train the Model.

Steps taken to train the model:

1) Video files are read and using OpenCV the number of frames the moving object stays for and its time duration is noted.
2) The file name, both the obtained parameters and the label(jog/walk) are appended to a numpy array
3) This numpy array is converted to a fata frame
4) Features and labels are sperated and are fitted to a logistic regression classifier to train the model
