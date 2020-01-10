The solution for task 1 is filtering 'Recommended' and 'Selected' columns for each 'user' files and creating new files for each 'user' .

task1.ipynb is the file for above mentioned solution.     

The approach for Task 2 is to find the pattern in which a particular doctor treats the patients and how each doctor's accupuncture points differ from each other. Individual "users" data is combined by taking the unique values of userid ,symptoms tuple(tuple formed using symptom 1 and symptom 2) and the points which they choose to treat that particular patient is stored in a list, it is then matched and joined with other "users" data  by searching common tuples and user's selected acupoints to find unique and common acupoints chosen by each "user" inorder to predict the acupoint chosen by 6th user(new user).


