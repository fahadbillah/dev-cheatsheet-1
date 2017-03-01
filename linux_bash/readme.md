# Create a linux bash script and run it

- go to a directory and open command terminal
- create a file
```
touch example.sh
```
- open the file
```
subl example.sh
```

- edit the file
- on the first line write
```
#!/bin/bash
```

- then add some codes in next lines
```
echo "I am a very good programmer"
ls
echo $HOME
echo $PATH
```
- save the file
- in the terminal write the command
```
$ chmod 777 example.sh
```
- the above command makes the example.sh readable, writable and executable by everyone
- then run the command using
```
$ ./example.sh
``` 
- or just

```
$ ./example
```

- the code will then run and do the processes