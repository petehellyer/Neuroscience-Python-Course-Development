# Exercises 

The level of complexity is described by the number of stars next to the title - the more stars there are, the more complex is the exercise.

## 1. Parse a corrupted file (⭐️⭐️)
There is a text file that is a MATLAB matrix where each row in the matrix is a row in the file and the columns in the matrix are separated by  `\t `. The matrix should only have numbers, but, because of some internal errors, the matrix has been corrupted and some of the lines contain words. Write a *function* that:
1. Import the file 
2. Excludes the rows with words
3. Returns the fixed matrix as a numpy array
4. Use the function to check that it works properly

**HINT**: To solve the exercise, you have to acess the file, and use a *for* loop and *if* statement.

## 2. Implement an abtash seifer (⭐️)
A seifer is a way to encode messages by mapping each letter to a different one. One ancient way to do this is called `the abtash seifer`. This seifer uses as key an inverted alphabet, so that `A` becomes  `Z`,  `B` becomes `Y`. Write two functions that implements the encoding and decoding process of the seifer. 

**IMPORTANT** -> the seifer must:
1. Ignore elements in a message that are not letter (e.g. numbers or spaces)
2. Be able to take as input the message both in capital letter and lowercase.


## 3. The RNA complementary (⭐️)
Transcription is the process in which DNA is converted to RNA. To do this, it is necessary to map each letter in a DNA sequence to its complemet `A -> U`, `T -> A`, `G -> C` and `C -> G`. Define a function that takes an input a DNA sequence and returns the RNA complementary.

## 4. Implement a Ceasar seifer (⭐️⭐️⭐️)
Another way to encode messages is through a Ceasar seifer. Here you are given a message and a key, which is a number, and the encoding is done by shifting the number in *key* places. So, if the key = 2, then `A` becomes `C`,  `B` becomes `D` and  `Z` becomes  `B` (and so on). Implement the encoding functin (and as a bonus the decoding) that takes as input a message and a key (with key having as default value 3) and returns the encoded message. 

**HINT #1**: the most efficinet way to implement a seifer is with a *dictionary*

**HINT #2**: to encode certain letter you will have to go back to the beginning of the alphabet. For this case, the *modulo* operator (%) is useful, which returns the remainder of the division of two numbers. 

**HINT #3**: if the *modulo* is too challenging, try with an *if* statement.

## 5. Fix the separated sentence (⭐️⭐️⭐️)
A sentence was written in 5 separate files and needs to be put together into a unique sentence. 


## 6. Cognitive data analysis (⭐️⭐️⭐️⭐️)
We have collected behavioural and cognitive data from 100 people as part of a study called GBIT (Great Britain Intelligence Test). The data consists in their performance in three cognitive tasks, as well as their demographics and measures of their mental health. This data are provided in two separate dataframes: `cognitive.csv` contains the results in the cognitive tasks, and `demographics.csv` contains the answers from questionnaires. The data were anonymised and a basic processing was already completed. The aim of this exercise is to properly clean the data and run some statistical tests to analyse them. 

    IMPORTANT: To be able to complete this exercise you must have completed the statistical theory and coding tutorial

1. Import the data in the format of a `pandas` dataframe.
2. Check the column headers, shape of the dataframe and types of columns. There is a column that should be an integer and is, instead a string. Detect that column and change the variable type.
3. Currently, the index of the dataframe is not easy to interpret. Change it and replace it with the values in the `user_id`
3. Find out which columns have missing values and how many they are for each column. If a column is more than 50% NA then drop it. Once you have filtered the columns, filter the dataframe for the remaining rows without missing values. 
4. Find out if there are duplicates in the dataframe. If there are two rows that are fully duplicated, then keep the second entry. If a column is duplicated in the  `user_id `,  `sex ` and  `Residence `, but not the others, then drop both rows. 
