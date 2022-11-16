# COE544-IEA-Project1
Supervised Machine Learning Model based on Optical Character Recognition
Libraries needed to run this project:
  1-scikit-image
  2-scikit-learn
  3-opencv-python
  4-tkinter
  5-pandas
  6-numpy
  
The GUI2.py script runs the whole project through a graphical user interface
The Pre_Processing.py script pre-processes the image and normalizes it to produce a skeletonized version of the image
The HOG.py, Zoning.py, Projection.py, Edges.py, and Profile.py scripts extract features from the processed image
The Classification.py script trains the SVM model on the training data set (provided in ./Data/Training_Data/data_set_1_training_data folder). The model (which is loaded in the ./Model folder)  will classify the input images.
