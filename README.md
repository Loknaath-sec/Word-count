# Exp-5a-Word Count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
1.PC
2.Anaconda - Python 3.7
## ALGORITHM: 
1. Open the file 
2. Read the contents
3. Split the text into words
4. Count and print the words
## PROGRAM:
~~~
# Program to find the Word count
# Developed by : P.LOKNAATH
# Register Number : 212223240080

num=0
with open("sample.txt","r") as f1:
    word_count=f1.read()
    word=word_count.split()
    num=len(word)
print("The number of words are in the file : ",num)

~~~
## OUTPUT:
![5a-i](https://github.com/Loknaath-sec/Word-count/assets/145742558/cae4a3a7-243b-4f97-84ca-3a4d2b601f65)

![5a-ii](https://github.com/Loknaath-sec/Word-count/assets/145742558/a5b1d939-4455-43a6-904d-b56b35f81ab3)
<br/>

## RESULT:
Thus the program is written to find the word count from a text.
