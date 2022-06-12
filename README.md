# SA-C-GENDER-CLASSIFIER
# Algorithm
1. To classify the gender of a person use the DeepFace library.
2. DeepFace library is developed based on deep learning algorithms.
3. Import the deepface class from DeepFace library, cv2 class from openCv2 library and Matplot library according to the requirements.
4. Load and display the imported image.
5. Pass the image to DeepFace library and analyze the image to predict gender of a person.
6. This prediction is stored in result variable.
7. Finally print the prediction using this algorithm.

## Program:
```
/*
Program to implement 
Developed by   : VEERAMALAI S
RegisterNumber :  2122202300556
*/
```

1. CODE :
```python
!pip install deepface
from deepface import DeepFace
import cv2
import matplotlib.pyplot as plt
img1=cv2.imread('12.jpg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img1,actions=['gender'])
print("Gender : ",result['gender'])
img2=cv2.imread('13.jpeg')
plt.imshow(img1[:,:,::-1])
plt.show()
result=DeepFace.analyze(img2,actions=['gender'])
print("Gender : ",result['gender'])
```

## OUTPUT:
![Screenshot 2022-06-12 195654](https://user-images.githubusercontent.com/75234790/173238144-bcbd1dc1-2861-4839-874b-27e5dc2a4cab.jpg)

![Screenshot 2022-06-12 195905](https://user-images.githubusercontent.com/75234790/173238145-57ba25ae-c66b-4035-b6c2-40330bf95210.jpg)


2. DEMO VIDEO YOUTUBE LINK:

https://youtu.be/jkW_r7xNT3M
