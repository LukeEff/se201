### 4.1.1.1

tilde slash foo slash bar

### 4.1.1.2

/Users/bill is the home directory
bill is the username
sonnets is the deepest in the hierarchy

### 4.1.1.3

They do not differ. ~ is shorthand for the home directory

### 4.2.1.1

We use the -p option in mkdir

### 4.2.1.2

mkdir -p foo/bar

### 4.2.1.3

ls ~ | grep o

### 4.3.1.1

cd and cd ~ do not differ. They each will take you to the home directory

### 4.3.1.2

cd text_files/
cd ../second_directory/

### 4.3.1.3

cd text_files/
touch nil

### 4.4.2.1

mkdir -p foo/bar
mv foo/bar foo/baz

### 4.4.2.2

cp -r text_files foo

### 4.4.2.3

cp text_files/* foo

### 4.4.2.4

rm -rf foo

### 4.5.1.1

mkdir foo && cd foo && echo "baz" > bar && echo bar && cd -

### 4.5.2.1

mkdir fails because foo already exists. No commands executed because the
double-ampersand will only run the following commands if the previous one
succeeded.

### 4.5.1.3

rm -rf / will delete the / directory, which contains all of the files and the
-rf option will run it without any confirmation.

### 4.5.1.4

Adding sudo to the beginning of it, so it is sudo rm -rf / will run the command
as a superuser, which is the highest level of power in the computer.
