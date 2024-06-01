# introduction_of_python

Hello World, this is my profile 

Python is a popular programming language: Created in 1991 by Guido van Rossum.

**Versatile:** Used for web development, software creation, data analysis, and more.

**Beginner-friendly:** Simple syntax like English with clear indentation rules.

**Efficient:** Runs on an interpreter for quick testing and development.

**Multi-paradigm:** Can be used procedurally, object-orientedly, or functionally.

**Example** Get your own Python Server

**print**("Hello, World!") 

**result**: **Hello, World!**
**Any problems that bother me or any new students have their solutions on this task.**




**Write a Python program to count the number of occurrences of each word in a given sentence.**

# diffine a function 

def count(sentence):

    # sentence convert in lower case 
    sentence = sentence.lower()
    # spliting sentence in to words 
    words= sentence.split()
    word_counts= {}
    
    # using for loop
    
    for word in words:
        if word in word_counts:
            word_counts[word] +=1
        else:
            word_counts[word] =1
            
          return word_counts
          
 # example  
 
sentence= ("i am amina iqbal.")
word_counts= count(sentence)
print(word_counts)

***time.strftime() function in Python***

Note: 

0 is a legal argument for any position in the time tuple; if it is normally illegal the value is forced to a correct one.
 

Syntax: time.strftime(format[, t])

Parameters : 

t – time in number of seconds to be formatted 

format – This is of string type. i.e. the directives can be embedded in the format string.

Return value: None


Many directives can be embedded in the format string, you can refer them here. 

Notes:
 

When used with the strptime() function, the %p directive only affects the output hour field if the %I directive is used to parse the hour.

The range really is 0 to 61; value 60 is valid in timestamps representing leap seconds and value 61 is supported for historical reasons.

When used with the strptime() function, %U and %W are only used in calculations when the day of the week and the year are specified.


# Import the strftime function from the time module

from time import strftime  

# Format and retrieve the current time in the specified format
# Format: Day of the week, day month year hour:minute:second + 1010 (timezone offset)
s = strftime(" %a, %d %b %Y %H:%M:%S + 1010")

# Print the formatted date and time string
print("Example:", s)
        
