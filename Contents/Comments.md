# Comments in Bash Scripting

\- Comments in bash script are used to make the code more understandable. You can also use comments to skip part of codes while debugging your script.

\- Single line comments starts with a `#` at the beginning of line.

### Single line comment Example :
```shell
#! /bin/bash

# This is a single line comment
echo "Hello world"  # This is inline comment

```

\- Multiline comment starts with `: ' ` and end with `'` as follows.
### Multiline Comment Example :
```shell
#! /bin/bash


: '
        this is a multiline comment
        this is a multiline comment
        this is a multiline comment
'

echo "Hello world"

```

### Output :
```
Hello world
```
