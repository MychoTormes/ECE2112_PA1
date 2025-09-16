# ECE2112_PA1: INTRODUCTION TO PYTHON PROGRAMMING


## 💻 ALPHABET SOUP PROBLEM
Create a function that takes a string and returns a string with its letters
in alphabetical order.

Example: 

alphabet_soup(“hello”) ➞ ehllo

alphabet_soup(“hacker”) ➞ acehkr

## 🟢 Background
The Steps:

1) Define alphabet_soup:

       def alphabet_soup(n)

3) Sort the letter alphabetically
    
        str = sorted(n)
    
4) Join letters togetter into a word 
    
         z = ''.join(str)
    
         return z

### 📌 Files
All the codes are done in this file.

        AlphabetSoup.ipynb
          
### 📍 Reference

        Python Cheat Sheet.pdf

## 💻 EMOTICON PROBLEM: 
Create a function that changes specific words into emoticons. Given a sentence
as a string, replace the words smile, grin, sad and mad with their corresponding emoticon:

Example:

emotify(“Make me smile”) ➞ Make me :)

emotify(“I am mad”) ➞ I am >:(

## 🟢 Background
The steps:

1) Define emoticon:
   
         def emoticon(n)

2) Verify the specific words to make into emoticons
    
         z = "smile" in n
    
         x = "grin" in n
    
         y = "sad" in n
    
         w = "mad" in n
    
3) Use replace() to replacing words to emoticons
    
         if z:
    
              a = n.replace("smile", ":)")
              print(a)
        
         elif x:
                a = n.replace("grin", ":D")
                print(a)
        
         elif y:
                a = n.replace("sad", ":((")
                print(a)
        
         elif w:
                a = n.replace("mad", ">:(")
                print(a)
        
### 📌 Files
All the codes are done in this file.

        Emonticon.ipynb

### 📍 Reference

        Python Cheat Sheet.pdf


## 💻 UNPACKING LIST PROBLEM: 
Unpack the list writeyourcodehere into three variables, being first,
middle, and last, with middle being everything in between the first and last element. Then print all three
variables.

Example: 

lst = [1, 2, 3, 4, 5, 6]

Output: 
first: 1 

middle: [2,3,4,5] 

last: 6

## 🟢 Background
The steps:

1) Defiine writeyourcodehere
   
        def writeyourcodehere(n)

3) Use the sequence containers indexing to identify the first, middle, and last
       
        print("First:", n[0])
       
        print("Middle:", n[1:-1])
       
        print("Last:", n[-1])
       
### 📌 Files
All the codes are done in this file.

        Unpacking List.ipynb

### 📍 Reference

        Python Cheat Sheet.pdf

### All of the answers for the Programming Assignment are made by Mycho Tormes
