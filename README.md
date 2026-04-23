# Homework 2 Code Guide
Welcome to Jasmine's ECON 470 HW 2 repository! Here you can find my code and answer key and below is a guide to navigating the repository. 

# Data Upload and Cleaning
Make sure to update any file paths used in my code to match your file paths (i.e. file/folder names, general folder structure). This applies for the .py file, data cleaning/uploading code, and the main code answering the homework questions. You can do this by using this code in any .ipynb file:

import os\
os.path.exists(path)

Data uploading and cleaning code can be found under the "datacode" folder. Double check that the relative paths referenced in the functions.py file match your file structure in Jupyter to get to the ma service area data files. 

Each year's data upload code is also provided in this folder. They have already been updated to match the size of the raw data files and the names provided in the class Jupyter notebook. Also, please make sure to create a folder named "data" within your folder for this assignment for the cleaned data files to be stored. 

# Homework Answer Code
The code for the homework questions can be found in the file "hw2code.ipynb". Again, double check that all paths have been updated to match your folder structure and names. Each question has its own section in the file. 

# Final Submission
To create a pdf for submission, navigate in terminal to your file for this assignment and run: 

run-quarto convert hw2code.ipynb

Then, open that new qmd file and add under the title section: 

echo: false

This will hide the code and only display the outputs. To clean this file up even more, update the title of the document itself, and feel free to delete any codeboxes that were used mainly to double check things like file size, column names, etc. unrelated to the homework answers themselves.

Once you are satisfied with your polished qmd, open terminal again and navigate to your file for this assignment. Run this code to render a submission-ready pdf:

run-quarto render hw2code.qmd --to pdf

Once the file is produced, make sure to rename it according to Dr. McCarthy's preferences and submit! 

Please feel free to email me at jasmine.zhao@emory.edu with any questions or concerns. 