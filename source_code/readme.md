# AWK
## Look and feel
```awk
awk '{ if (length($0) > max) max = length($0) } END { print max }' geeksforgeeks.txt
```
## Source
```
...awk
awk '{ if (length($0) > max) max = length($0) } END { print max }' geeksforgeeks.txt
...
```


# SHELL
## Look and feel
```shell

#!/bin/bash

# example of using arguments to a script
echo "My first name is $1"
echo "My surname is $2"
echo "Total number of arguments is $#" 
```
## Source
``` shell

#!/bin/bash

# example of using arguments to a script
echo "My first name is $1"
echo "My surname is $2"
echo "Total number of arguments is $#" 
```