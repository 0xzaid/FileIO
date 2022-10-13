# Test the program
```$ stack test```

# Build the app
```$ stack build```

# Run the app
```$ stack exec printFiles "share/test.txt"```
============ share/a.txt
Content of a.
============ share/b.txt
Content of b.
============ share/c.txt
Content of c.
Characters = 39

If no arguments are provided, prompt the user to enter one
```
$ stack exec printFiles
Enter filename: (<- your program's prompt)
share/test.txt  (<- the user types this)
============ share/a.txt
Content of a.
============ share/b.txt
Content of b.
============ share/c.txt
Content of c.
Characters = 39
```

# install the app
```$ stack install```

then use the app from anywhere
```$ printFiles "share/test.txt"```
