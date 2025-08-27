# Programming
Notebooks during my ECE2112 class

INTRODUCTION TO PYTHON PROGRAMMING

Assignment 1
Munsayac, Angela Ysabhelle C. 
2ECE-B

**Alphabet Soup Numbers**

#define what to use in the program 
    
#for chronological order of the letters 
#s string, and str.lower is for the lowercase
#combine the strings in one

#output of the program

**Emoticon Problem**

def my_function(sentence):                           #declared function in the program 
   
    sentence = sentence.replace("smile", ":)")       #where we replace the words into emoticons
    sentence = sentence.replace("grin", ":D")
    sentence = sentence.replace("sad", ":(")
    sentence = sentence.replace("mad", ">:(")
    return sentence
​
 
#output of the program
text = input("Enter a sentence: ")                  #where user will input a sentence
converted = words_to_emoticons(text) 
print("With emoticons:", converted)                #output of emoticons
​

**Unpacking List Problem**


​
numbers = input("Enter numbers: ")              #used function int
yourcode = list(map(int, numbers.split()))      #declaring yourcode as int and it split the integers
​
first = yourcode [0]                            #used a slicing method to separate the inputted numbers
middle = yourcode[1: -1]
last = yourcode[-1]
​
#Output of the program 
print("First:" , first)
print("Second: ", middle)
print("Last: ", last)
