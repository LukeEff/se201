### 3.1.1.2

95635 bytes.

### 3.1.1.4

Shows all files (including hidden) with human readable byte counts in reverse
time sorted long form -> ls -rtlha 

### 3.2.2.2

head -n 30 sonnets.txt


### 3.2.2.3

head -n 2620 sonnets.txt | tail -n 14


### 3.2.2.4

tail -f does not stop when the end of a file is reached. It will wait for
additional data to be appended to the input. It lets you see files that are
actively changing.

### 3.4.1.1

grep -n rose sonnets.txt


### 3.4.1.3

grep -n rose sonnets.txt | head -n 1

### 3.4.1.4

grep Rose sonnets.txt

### 3.4.1.5

grep Rose sonnets.txt | grep -v rose | wc 

### 3.5.1.2

history | wc

The count is 500 

### 3.5.1.3

history | grep -i curl

or

history | grep curl

### 3.5.1.4

Executing !2 would execute the second command in your history 

### 3.5.1.5

The -O option is saying to write the output of the command to a local file that
is named like the remote file we get and the -L option means location of the
remote file like the http address.

