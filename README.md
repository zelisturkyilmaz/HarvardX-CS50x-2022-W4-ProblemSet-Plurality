# CS50's Introduction to Computer Science
## HarvardX - CS50x
### Week 4 Problem Set - Plurality.c
<hr>


### Assignment and Requirements:
Write and execute the program that takes candidates as command-line argument, prompts user for votes and print out the winner (or winners) of the election.

Program should behave per the examples below:

```
$ ./plurality Alice Bob
Number of voters: 3
Vote: Alice
Vote: Bob
Vote: Alice
Alice
```

```
$ ./plurality Alice Bob Charlie
Number of voters: 5
Vote: Alice
Vote: Charlie
Vote: Bob
Vote: Bob
Vote: Alice
Alice
Bob
```

#### Compiling And Execution:

Before execution of the program, it must be compiled with a compiler, translating it from source code into machine code.\
Execute the command below in the Command Line to do that:

```C
make plurality
```

Execute the program by executing the below:
```C
./plurality *args
```
substitute valid candidates in place of ```*args```
