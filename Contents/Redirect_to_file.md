# Redirect To file

\- We can capture the output from previous operations and redirect to a new file using `>` and `>>` operators as  follows.

### Example :
```shell
#! /bin/bash

echo "Hello world" > test_file.txt

```
### Output :
A new test_file.txt will be created with the contents as "Hello world". Nothing will be printed on the screen as we are redirecting the output to a new file.

\- The `>` operator always replaces the content of the file with new data.

\- If we want to append the output to a file, we have to use `>>` operator as follows.

### Example :
```shell
#! /bin/bash

echo "This is another line" >> test_file.txt
```

### Output :
```
~$ cat test_file.txt

Hello World This is another line.
```


