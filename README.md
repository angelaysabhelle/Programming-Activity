# Programming Activity 
Notebooks during my ECE2112 class 

Assignment 2
Munsayac, Angela Ysabhelle C. 
2ECE-B

**Programming Assignment 2 
Numerical Python**

**NORMALIZATION PROBLEM:** Normalization is one of the most basic preprocessing techniques in data analytics. This involves centering and scaling process. Centering means subtracting the data from the mean and scaling means dividing with its standard deviation.

In this program, I am tasked to create a random 5x5 ndarray and that array I will store it to variable X. 
1.	First let us import numpy as np. Let x will be a storage for the random 5X5 ndarray.
X = np.random.rand(5,5)
2.	Let’s put the formula to get the mean and standard deviation of variable x.
For the mean:
			mean_ x = x.mean()
			std_x = x.std()
 Formula to get the mean or z-score normalization
			x_normalized = (x - mean_x) / std_x 
3.	The output and printing the result of the 5X5 array
print("\nNormalized x:\n", x_normalized)  


**DIVISIBLE BY 3 PROBLEM:** Create the following 10 x 10 ndarray.
𝐴 =[1 4 ⋯ 81 100
⋮ ⋮ ⋱ ⋮ ⋮
⋮ ⋮ ⋱ ⋮ ⋮
⋮ ⋮ ⋱ ⋮ ⋮
8281 8464 ⋯ 9801 10000]
which are the squares of the first 100 positive integers.
From this ndarray, determine all the elements that are divisible by 3. Save the result as div_by_3.npy
In this program, I am tasked to create an array that contains the squares of the first 100 positive integers. Then I will check which of those numbers are divisible by 3.

 1. First, I import numpy as np:
import numpy as np
2.  I generated the array using a list
 [(i + 1) ** 2 for i in range(100)] and reshaped it into a 10x10 matrix with 
reshape(10, 10)
3. After creating the array, I checked which numbers in the array are divisible by 3 using the condition: 
	a % 3 == 0
    Storing array new numbers will be called dibv_by_3
4. Next, is that in this line I counted the array that is divisible by 3 and sum it up.
	np.sum(a % 3 == 0
	div_by_3.sum()
5. Lastly,  , I printed the original 10x10 array, the numbers divisible by 3, how many such numbers there are, and the total sum of those numbers. This NumPy function with arrays, makes the task much faster and easier. 






















# Programming Activity 
Notebooks during my ECE2112 class 

INTRODUCTION TO PYTHON PROGRAMMING

Assignment 1
Munsayac, Angela Ysabhelle C. 
2ECE-B

**Alphabet Soup Numbers**

ALPHABET SOUP PROBLEM: Create a function that takes a string and returns a string with its letters
in alphabetical order.
Example: alphabet_soup(“hello”) ➞ ehllo
alphabet_soup(“hacker”) ➞ acehkr

Firstly, I browse to our notes in canvas to have an idea on the code and functions that I can use in creating this program. But before that, our professor gave us an task to download the program language that we are gonna use for this sem.
- Opened the Anaconda Navigator, and select the Jupyter Notebook to write a code in Python.
- After that, I opened my canvas to check the assignment and try to figure it out.
- While writing in this notebook, I'm currently searching on how to use the other functions that can help me to build the program.
  
**Steps in Coding the Soup Problem:**
1. Define a function on what to use in the program:
   def alphabet_soup(s):
2. For chronological order of the letters we are going to use the
   If char.isalpha(), then [char for char in s]
   - goes over every character in the string s in a loop. Eliminates punctuation,       digits, and spaces and only leaves alphanumeric characters.
3. s string, and str.lower is for the lowercase and sorts the filtered letters 
4. Combine the strings in one
   return ''.join(letters)
6. Output of the program should list alphabetically the word inputted by the user

**Emoticon Problem**
Create a function that changes specific words into emoticons. Given a sentence
as a string, replace the words smile, grin, sad and mad with their corresponding emoticon

1. Define the function. For this problem i used:
   def my_function(sentence):
   sentence- string which the user will input
2. Replacing the words into emoticons
   .replace() i used this to replace the string into a smiley emoticon assignment
3. Return the modified sentence
   return sentence
4.User Input
   text = input("Enter a sentence: ")
5. Call the function
   converted = words_to_emoticons(text) when the user input as a parameter when       calling my_function.
6. Prints the output entered by the user.
​   print("With emoticons:", converted)

**Unpacking List Problem**
Unpack the list writeyourcodehere into three variables, being first,
middle, and last, with middle being everything in between the first and last element. Then print all three
variables

1.Take the user input
  numbers = input("Enter numbers: ") prompting to enter multiple numbers
2. Converts the inputted string list as integers
   yourcode = list(map(int, numbers.split()))
   -List, and separate the inputted integers.
3. Specifying the parts of the list created
    first = yourcode [0]                            
    middle = yourcode[1: -1]
    last = yourcode[-1]
   -used a slicing method to separate the inputted numbers
 4. Print the output of the program - Display each extracted part of the list w labels
    print("First:", first)
    print("Second:", middle)
    print("Last:", last)

In this activity, the basic python skills that we used is simple but powerful when we master it. These are the stepping stone to become skillfull in Python. 



