## EXNO-3-DS

# AIM:
To read the given data and perform Feature Encoding and Transformation process and save the data to a file.

# ALGORITHM:
STEP 1:Read the given Data.
STEP 2:Clean the Data Set using Data Cleaning Process.
STEP 3:Apply Feature Encoding for the feature in the data set.
STEP 4:Apply Feature Transformation for the feature in the data set.
STEP 5:Save the data to the file.

# FEATURE ENCODING:
1. Ordinal Encoding
An ordinal encoding involves mapping each unique label to an integer value. This type of encoding is really only appropriate if there is a known relationship between the categories. This relationship does exist for some of the variables in our dataset, and ideally, this should be harnessed when preparing the data.
2. Label Encoding
Label encoding is a simple and straight forward approach. This converts each value in a categorical column into a numerical value. Each value in a categorical column is called Label.
3. Binary Encoding
Binary encoding converts a category into binary digits. Each binary digit creates one feature column. If there are n unique categories, then binary encoding results in the only log(base 2)ⁿ features.
4. One Hot Encoding
We use this categorical data encoding technique when the features are nominal(do not have any order). In one hot encoding, for each level of a categorical feature, we create a new variable. Each category is mapped with a binary variable containing either 0 or 1. Here, 0 represents the absence, and 1 represents the presence of that category.

# Methods Used for Data Transformation:
  # 1. FUNCTION TRANSFORMATION
• Log Transformation
• Reciprocal Transformation
• Square Root Transformation
• Square Transformation
  # 2. POWER TRANSFORMATION
• Boxcox method
• Yeojohnson method

# CODING AND OUTPUT:
![DS exp 3 ipynb - Colab_page-0001](https://github.com/user-attachments/assets/7eab9d37-39c9-462e-a8db-6d9d200980cc)
![DS exp 3 ipynb - Colab_page-0002](https://github.com/user-attachments/assets/5ec67d89-d68a-4958-83d2-130f1c46e8ab)
![DS exp 3 ipynb - Colab_page-0003](https://github.com/user-attachments/assets/4a14cf4c-c393-42d2-87bd-f566cfefa738)
![DS exp 3 ipynb - Colab_page-0004](https://github.com/user-attachments/assets/fb8238fc-0265-4aee-be97-c8307fa02ebc)
![DS exp 3 ipynb - Colab_page-0005](https://github.com/user-attachments/assets/616b4451-83c3-498f-8150-54644f2a1003)
![DS exp 3 ipynb - Colab_page-0006](https://github.com/user-attachments/assets/1d20bc97-754d-4784-aefb-c26b3be72f3f)
![DS exp 3 ipynb - Colab_page-0007](https://github.com/user-attachments/assets/f6bfa8a1-0ecd-414b-a202-7b5987b35f73)
![DS exp 3 ipynb - Colab_page-0008](https://github.com/user-attachments/assets/92b2e2ec-d137-45ae-b73e-f49df62abea6)
![DS exp 3 ipynb - Colab_page-0009](https://github.com/user-attachments/assets/4144da3e-acc8-467c-bf2a-30a424d623e8)

       
# RESULT:
Thus we have read and performed Feature Encoding and Transformation process and save the data to a file.
   

       
