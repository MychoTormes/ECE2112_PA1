# ECE2112_PA1: INTRODUCTION TO PYTHON PROGRAMMING

ALPHABET SOUP PROBLEM: Create a function that takes a string and returns a string with its letters
in alphabetical order.

The function that I created:

def alphabet_soup(n):

    # sorting letter alphabetically
    
    str = sorted(n)
    
    # join letters togetter into a word 
    
    z = ''.join(str)
    
    return z
    

EMOTICON PROBLEM: Create a function that changes specific words into emoticons. Given a sentence
as a string, replace the words smile, grin, sad and mad with their corresponding emoticon:

The function that I created:

def emoticon(n):

    # verity the specific words to make into emoticons
    
    z = "smile" in n
    
    x = "grin" in n
    
    y = "sad" in n
    
    w = "mad" in n
    
    # replacing words to emoticons
    
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
        

UNPACKING LIST PROBLEM: Unpack the list writeyourcodehere into three variables, being first,
middle, and last, with middle being everything in between the first and last element. Then print all three
variables.

The fuction that I created:

def writeyourcodehere(n):

       # using sequence containers indexing
       
       print("First:", n[0])
       
       print("Middle:", n[1:-1])
       
       print("Last:", n[-1])
       
