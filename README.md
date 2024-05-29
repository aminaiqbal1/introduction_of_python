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

# Write a Python program to count the number of occurrences of each word in a given sentence.
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
        
