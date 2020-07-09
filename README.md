## mIR


#### Overview 

the source code of SIGMOD'2021 submission with Paper ID 170

#### Prerequisities

1. g++/gcc
2. make
3. qhull
#### Files

##### main.cpp

The entry of program, it parses parameters, construct R-tree and load user.  


#### advanced.h and advanced.cpp

Code for advanced solution  



#### Run the program
```
make
./program -m 1 -d 2 -k 2 -n 2 -i index.txt -f option.txt -u user.txt  



```


#### Configuration

`-f` path for option file  
`-i` path for R-tree index  
`-u` path for user preference  
`-n` number of option  
`-d` dimension  
`-k` parameter k  
`-m` parameter m  