# Word-count
## AIM:
To write a python program for getting the word count from a text.
## EQUIPEMENT'S REQUIRED: 
PC Anaconda - Python 3.7
## ALGORITHM: 
Step 1: Create a txt file to count the number of word in that file.

Step 2: Open the txt file in read mode using open().
 
Step 3: Using split() function to split the words in txt file and count it

Step 4: Save the python program using.py extention.

Step 5: Run the python progra in terminal to get the output.

Step 6: Number of words in the file is displayed as the output

## PROGRAM:
```
Developed by: Archana.k
Ref.no: 22009150
num_words = 0
with open('text.txt'.'r') as f1:
     for i in f1:
         words = i.split()
     num_words += len(word)
print("number of words in the file = {}".format(num_words))
```
### OUTPUT:
![Screenshot 2023-01-26 194932](https://user-images.githubusercontent.com/118708624/214859289-a99cea10-ea4c-480f-999a-326c6e060e53.png)

## RESULT:
Thus the program is written to find the word count from a text.
