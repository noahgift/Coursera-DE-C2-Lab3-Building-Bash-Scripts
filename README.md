# Coursera-DE-C2-Lab3-Building-Bash-Scripts
Build Bash Scripts Lab

## Goal:   Build Bash Command Line Tool that accepts two arguments

You have learned to build Bash command-line tools.  This exercise helps you master this concept.

Let's create a Bash Command Line Tool that accepts two arguments.  The current example accepts two arguments `--count` and `--phrase`.

To run the command you get the following output:

```
./cli.sh --count 5 --phrase "hello world"
hello world
hello world
hello world
hello world
hello world
```

### Part 1: Perform the following steps

1.  Change the `--count` option to be named `--number`.
2.  Change the the `--phrase` option to be name `--message`.
3.  Rerun the command-line tool

### Part 2:  Change the phrase generate

1.  The `phrase_generator()` bash function prints out the phrase you entered as the second argument via `echo "$2"`.  Change function so it will print out the phrase with the following appended to the front:  `You entered phrase:`.

