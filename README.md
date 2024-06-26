# Image-Processing
A Jupyter notebook using Random Forest modelling to process handwriting.

Import the following:
-numpy
-matplotlib.pyplot
from sklearn.model_selection import train_test_split
from sklearn.ensemble import RandomForestClassifier
from sklearn.model_selection import GridSearchCV
from sklearn.metrics import confusion_matrix
from sklearn.metrics import ConfusionMatrixDisplay
from sklearn.metrics import accuracy_score, precision_score, recall_score, f1_score

# Load dataet from sklearn
from sklearn.datasets import load_digits
digits = load_digits()
