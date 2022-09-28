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
1. Ignors elements in a message that are not letter (e.g. numbers or spaces)
2. Be able to take as input the message both in capital letter and lowercase.


## 3. The RNA complementary (⭐️)
Transcription is the process in which DNA is converted to RNA. To do this, it is necessary to map each letter in a DNA sequence to its complemet `A -> U`, `T -> A`, `G -> C` and `C -> G`. Define a function that takes an input a DNA sequence and returns the RNA complementary.


## 5. Cognitive data analysis (⭐️⭐️⭐️)
We have collected behavioural and cognitive data from 100 people.