# Computer Vision
## Data
The data is taken from the ChaLearn Looking at People website and is located in the `/datasets/faces/` folder. You have one folder containing all the images (`/final_files`) and a CSV file, `labels.csv`, with two columns: `file_name` and `real_age`.<br>

To extract data from the folder, you can use the new method <i>ImageDataGenerator</i> - `flow_from_dataframe(dataframe, directory, ...)`. This method will help you load the images and their corresponding labels for your data analysis or machine learning tasks.

## Task
Build a model that will approximate a person's age based on a photo. You have a dataset of photos of people along with their age information at your disposal.

<a href="https://github.com/DimaDoesCode/Yandex_Practicum-Computer_Vision/blob/master/computer_vision/computer_vision.ipynb">To view the Jupyter Notebook code of the research, click on this link.</a>

## Libraries used
<i>matplotlib.pyplot, os, pandas, PIL, random</i>