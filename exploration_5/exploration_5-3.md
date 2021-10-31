### 1.

Tree.

### 2.

~, the tilde

### 3.

. represents the current directory you are in

.. represents the parent of the current directory you are in

### 4.

The problem is they're making a copy of it with a new name. Not to mention that
the command wouldn't even successfully execute since you need to use -r when
copying directory. If it WAS successfully executed, eg cp -r hero villain, we
would still have the original directory and its contents, but there would also
be the villain directory as well now with a copy of the contents from hero. 

To rename, they want to do:
mv hero villain

