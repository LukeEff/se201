### 2.1.1.1

echo "From fairest creatures we desire increase." > line_1.txt
echo "That thereby beauty's rose might never die." > line_2.txt

### 2.1.1.2

cat line_1.txt > sonnet_1_copy.txt
cat line_2.txt >> sonnet_1_copy.txt

-- OR --

echo $(cat "line_1.txt") > sonnet_1_copy.txt
echo $(cat "line_2.txt") >> sonnet_1_copy.txt

### 2.1.1.3

cat line_2.txt line_1.txt > sonnet_1_reversed.txt

### 2.2.2.1

ls s*

### 2.2.2.2

ls -rtl *onnet*

### 2.2.2.3

ls -rtl -a 

### 2.3.2.1

echo "hello, world" > foo.txt
cp foo.txt bar.txt
diff foo.txt bar.txt

### 2.3.2.2

cat foo.txt > baz.txt

### 2.3.2.3

cat foo.txt bar.txt > quux.txt

### 2.3.2.4

rm -f nonexistent does not notify the user that there was no file to delete, but
rm nonexistent does notify the user.

### 2.4.1.1

echo "FRom faireſt creatures we deſire increaſe, That thereby beauties Roſe might neuer die, But as the riper ſhould by time deceaſe, His tender heire might beare his memory: But thou contracted to thine owne bright eyes, Feed’ſt thy lights flame with ſelfe ſubſtantiall fewell, Making a famine where aboundance lies, Thy ſelfe thy foe,to thy ſweet ſelfe too cruell: Thou that art now the worlds freſh ornament, And only herauld to the gaudy ſpring, Within thine owne bud burieſt thy content, And tender chorle makſt waſt in niggarding:    Pitty the world,or elſe this glutton be,    To eate the worlds due,by the graue and thee." > sonnet_1_complete.txt

cat sonnet_1_complete.txt

### 2.4.1.2

touch foo
mv foo bar
cp bar baz

### 2.4.1.3

ls b*

### 2.4.1.4

rm b*

### Bonus

I see what I see because the file I cat into is in machine code, so it is is not
human-readable. This is probably for speed, since it wouldn't make sense to
compile the language each time I use rm or use an interpretted language to run
the command.
