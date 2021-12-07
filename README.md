# Alphabet-Detection C123
 * *We wrote a prediction algorithm which would detect the numbers from the given images.*

## Used
 * *Using data from ML library*
 * *Logistic regression*
 * *Using open CV*

## Steps To Create A Prediction Algorithm To Detect Alphabets (Part - 2)
 * *We imported all the necessary libraries.*
 * *We fetched the data from the open ml library/load data.*
 * *.**venv** creates a package. Even if the version is updated it works with the new version.To activate it we have to py -m venv venv. Then write click on scripts folder and open in terminal then **./activate.bat** to activate venv.*
 * *We were likely to get an error. So we introduced the concept of SSL to avoid the error (**Code is given below**).*
 * *We split the data to train and test the prediction model.*
 * *We fit the data into the model using Logistic Regression and checked the accuracy of the model.*
 * *We used the camera and captured every frame of it*
 * *We created a rectangle at the center of the video as the model will only detect the digit inside that rectangle. And also changed the color of the video to gray.(**Code is given below**)*
 * *We converted the image we got into PIL format to use it again and resized it to 28.*
 * *We then inverted the image to make it scalar and give it an value between 0 and 255.*
 * *Then we converted this data into an array and passed it to the model for prediction.*
 * *We displayed the resulting frame and added key control to stop the model.*
 * *We code to close the active windows when the program is closed.*

## Code is given below 
  ![123](https://user-images.githubusercontent.com/74312429/144367467-37fba548-26f1-42e0-951e-7e42b8925a00.jpg)
  ![SharedScreenshot](https://user-images.githubusercontent.com/74312429/144367364-c5db30cd-c7a3-4571-bec5-0c355d1ef4b6.jpg)
  ![SharedScreenshot1](https://user-images.githubusercontent.com/74312429/144367419-14504bc8-225a-40a0-ba0e-050ea6d6af10.jpg)
