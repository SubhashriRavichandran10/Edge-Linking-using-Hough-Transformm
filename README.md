# Edge-Linking-using-Hough-Transformm
## Aim:
To write a Python program to detect the lines using Hough Transform.

## Software Required:
Anaconda - Python 3.7

## Algorithm:
### Step1:

Import all the necessary modules for the program.
### Step2:

Load a image using imread() from cv2 module.
### Step3:

Convert the image to grayscale.
### Step4:

Using Canny operator from cv2,detect the edges of the image.
### Step5:

Using the HoughLinesP(),detect line co-ordinates for every points in the images.Using For loop,draw the lines on the found co-ordinates.Display the image.
## Output

### Input image and grayscale image

<img width="581" height="414" alt="image" src="https://github.com/user-attachments/assets/1fec914f-2abb-4e92-b520-5b3577ce2563" />


<img width="599" height="435" alt="image" src="https://github.com/user-attachments/assets/8c608bd5-8598-43de-9970-20ed4630e6d3" />


### Canny Edge detector output



<img width="584" height="435" alt="image" src="https://github.com/user-attachments/assets/ee3b9ee5-6460-4d62-bab3-44bd87bd3f10" />




### Display the result of Hough transform



<img width="556" height="430" alt="image" src="https://github.com/user-attachments/assets/331fe6ed-0e9d-4494-9593-55a9ac208297" />

## Result:


Thus, the image has been successfully converted.
