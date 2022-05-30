# HW-Saver-LLP-internship-task

### Step 1:- Understanding the problem statement.

### Step 2:- Loaded Example_Technical_Skills.csv.

### Step 3:- preprocessing done:- Lower case conversion and puntuation handled.

### Step 4:- Word seperated in order to match the techincall skill return in different form.

### Step 5:- Made a word cloud.

### Step 6:- Loaded Raw_Skills_Dataset.csv and removed null, nan, -.

### Step 7:- Used step 4 extracted word in order to mark them technical or non technical.

### Step 8:- After marking them preprocessed the words present in Raw_Skills_Dataset.csv.

### Step 9:- Lower case conversion and puntuation handled.

### Step 10:- A new dataset made from output of step 7,8,9.

### Step 11:- Loaded sub4 (new dataset).

### Step 12:- Made X variable by bring all unique words as columns and mapin word present with them in the setence/skill fetched.

### Step 13:- Made y variable containing whether technical skill present or not in x.

### Step 14:- Split dataset into train and test.

### Step 15:- Made a MultinomialNB model to see the pattern and further chossing tech skill.

### Step 16:- Model evaluatin using confuision matrix and classification report.

### Step 17:- if any setnce even part by part present and can be remade by using a number of different sentenses present in sub4 dataset then it can be even classified as technical skill or not.
