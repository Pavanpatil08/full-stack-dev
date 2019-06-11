# Week 1 - Day 2

**NOTE:** Follow the instructions carefully and follow coding discipline

## FSD.W1.2.A (10 min)

- Go to your home directory `cd ~` and create a folder called `assignments`   
- Create a folder called `week1` inside `assignments` folder  
- Create a folder called `day2` inside `week1` folder  
- Navigate to the folder `assignments/week1/day2` 
- All the work should be in this folder

## FSD.W1.2.B (40 min)

**NOTE: SAVE ALL THE COMMANDS ON HOW YOU ARRIVED AT THE ANSWER YOU NEED TO SUBMIT THEM**

Download the file https://raw.githubusercontent.com/masai-school/assignments-data/master/data/junk/marks_rand_2000.csv

The files contains marks the data of 2000 students from India and Pakistan one for each line in the below format

``` 
23 India 5cf9c9be70765c6c741bd34a
43 Pakistan 5cf9c9be70765c6c741bd352
.
.

```
1. Find the total number of students from India

ANSWER 
1500

Commands on how you got the answer

```
<COMMAND 1>
<COMMAND 2>
<COMMAND 3>
```
2. No of students from Pakistan who are in top 100 list based on the marks scored
```
ANSWER
28
```

Commands on how you got the answer

```
<COMMAND 1>$ head -n 100 pak1.txt
<COMMAND 2>
<COMMAND 3>
```
3. Top 3 students from India based on the marks scored
```
ANSWER
```99 India 6cf9c9be70765c6c741bd60a
99 India 6cf9c9be70765c6c741bd5aa
99 India 6cf9c9be70765c6c741bd577

Commands on how you got the answer

```
<COMMAND 1> sort -r india_stud.csv >ind.txt
<COMMAND 2>head -n 3 ind.txt
<COMMAND 3>
```
4. Bottom 5 students from Pakistan based on the marks scored
```
ANSWER
```83 Pakistan 5cf9c9be70765c6c741bd5ed
17 Pakistan 5cf9c9be70765c6c741bd62b
96 Pakistan 5cf9c9be70765c6c741bd5cd
71 Pakistan 5cf9c9be70765c6c741bd64f
81 Pakistan 5cf9c9be70765c6c741bd681

Commands on how you got the answer

```sorted and created new file
<COMMAND 1>less pak.csv
<COMMAND 2>tail -n 5 pak.csv
<COMMAND 3>
```

## FSD.W1.2.C (30 min)

**NOTE: SAVE ALL THE COMMANDS ON HOW YOU ARRIVED AT THE ANSWER YOU NEED TO SUBMIT THEM**

Clone the repo https://github.com/dwmkerr/hacker-laws inside `assignments/week1/day2` folder

1. Find the total number of commits done by the user with the name `Dave`

```
ANSWER 
91
```

Commands on how you got the answer

```
<COMMAND 1> grep Dave auth.txt
<COMMAND 2> sort -i auth1.txt
<COMMAND 3> wc -l auth1.txt
```

2. Find the total no of commits done in the month of April

```
ANSWER 10
```
Commands on how you got the answer

```
<COMMAND 1>grep Apr auth.txt
<COMMAND 2>grep Apr auth.txt >auth1.txt
<COMMAND 3>wc -l auth1.txt
```

3. Find the total no of commits done in the year 2018

```
ANSWER 33
```
Commands on how you got the answer

```
<COMMAND 1>grep 2018 auth.txt
<COMMAND 2> grep 2018 auth.txt > dat.txt
<COMMAND 3> wc -l dat.txt
```

## FSD.W1.1.D (20 min)

- Clone the repo https://github.com/masai-school/full-stack-dev inside `~/repos` folder
- Navigate to the folder `~/repos/full-stack-dev/`
- Copy the `course/week_1/day_1/w1_day_2_assignments.md` file to the `test` repository which should be at `~/repos/test`
- Open the file `w1_day_2_assignments.md` in the text editor using GUI and fill all the answers
- Sync your `test` repo online with the solutions
