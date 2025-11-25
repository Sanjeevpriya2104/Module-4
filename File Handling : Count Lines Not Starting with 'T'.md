# 4(E) File Handling in Python: longest word in a file

##  Aim
To write a Python program that function to find the longest word in a file.`.

## Algorithm
1.Start

2.Read the file path from the user or use a given file path.

3.Open the file in read mode.

4.Read the entire content of the file using .read().

5.Split the content into a list of words using .split().

6.Initialize a variable longest_word with an empty string.

7.Traverse each word in the list:

8.If the current word's length is greater than the length of longest_word,
update longest_word with the current word.

9.After the loop, longest_word will contain the longest word.

10.Return the longest word.

11.End


## Program
```
def create_file(file_path, content):
    with open(file_path, 'w') as file:
        file.write(content)

# Function to find the longest word in a file
def find_longest_word(file_path):
    with open(file_path,'r')as file:
        c=file.read()
        w=c.split()
        l=""
        for i in w:
            if len(i)>len(l):
                l=i
        return l
```

## Output
<img width="1009" height="336" alt="Screenshot 2025-11-25 205339" src="https://github.com/user-attachments/assets/184eecdc-d806-4dbf-b6a0-b6b217298cdf" />


## Result
progeamme executed successfully
