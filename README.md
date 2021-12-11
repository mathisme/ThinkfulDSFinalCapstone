# Thinkful Data Sciencce Final Captstone: Predict Total Cholesterol Level
My final capstone project for Thinkful's Data Science Flex Program.  For this capstone we were to think of a data science product, create a model, and present it in a presentation.  As someone with high cholesterol, I decided to do regression with NHANES data to predict total cholesterol level.  I felt it would be beneficial to health apps to be able to estimate a persons cholesterol level without the need for lab tests. If total cholesterol is predicted to be above 200, the health app can then ask the person if they have had their cholesterol checked recently.  I plan to redo this project to predict bad cholesterol instead of predicting total cholesterol.

# Included in this repository

# Steps

# Discoveries/Reflections
* When exploring the data, I discovered that <b>over half</b> of those with a total cholesterol level over 200 have never been told by a doctor they have high cholesterol.  This reinforces the need for a model to estimate cholesterol levels.
* The models all struggled predicting extreme values.  As the distribution for total cholesterol had outliers, a tool like SMOGN may have been helpful.
* As the dataset contained over 100 files and over 1500 variables, I chose to use variables that could effect cholesterol level based on online research I have done.  It would be intereting to explore using other variables.

# Tools used
* Pandas
* Matplotlib
* Scikit-learn
* Keras

# Tasks for the future
I am planing to redo this project using bad cholesterol instead and so not listing future tasks.
