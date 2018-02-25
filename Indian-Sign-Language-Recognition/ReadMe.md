The project is about Indian Sign Language recognition.
The making data.ipynb contains the code that was used to make the data, detect skin etc and all the preporcessing steps required for the project
The training CNN.ipynb contains the code for the final CNN model and the decision tree model. Confusion metrics and other evaluation steps are performed in this code.
The data file contains more than 9500 data points with 3072 columns in each therefore, it is not feasible to send over the data.
However, visualization is done in both the ipynb codes and also in project report.pdf
Skin_NonSkin.txt is the file for skin detection training. The first 3 column in this file are R,G,B values of a pixel and the fourth is the class it belongs to : Skin or no skin
haarcascade_frontalface_default.xml is used for casscade to detect skin.
The haar cascade used here is obtained from https://github.com/opencv/opencv/tree/master/data/haarcascades