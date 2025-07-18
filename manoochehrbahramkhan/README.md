# Reading files f1 and f2

This project only contains two files: `f1` and `f2`.  
You can read them easily using the following code:

## How to read the files

```python
with open('file1', 'r') as file1:
    content1 = file1.read()
    print('Content of file file1:')
    print(content1)

with open('file2', 'r') as file2:
    content2 = file2.read()
    print('Content of file file2:')
    print(content2)
