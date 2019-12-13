# Human Or Horse Classifer using CNN

[Human Or Horse Classifer using CNN in Google Colab](https://colab.research.google.com/github/swetabehera04/Horse_Human_Classifer_using_CNN/blob/master/Horse_Human_Classifier_using_CNN.ipynb)

![horsehuman](/horse.jpg)

## How to run the code in Colab

1-Run all the cells in Colab

2-On running the last cell i.e. 
```
from google.colab import files
uploaded = files.upload()
```
; you may run into this problem :

```
Upload widget is only available when the cell has been executed in the current browser session. Please rerun this cell to enable.
```
In this case , if rerunning the cell  doesn't work , that indicates that you have disabled cookies in your browser.

To resolve this (On Chrome):
 Settings -> Advanced -> Site Settings -> Cookies and site data -> Clear on exit (Click on 'add' to add -> https://[*.]googleusercontent.com:443 )  
 
 3- After running all of the cells , you can choose 1 or more files from file system, it will then upload them, and run them through the model, giving an indication of whether the object is a horse or a human.
 
 
