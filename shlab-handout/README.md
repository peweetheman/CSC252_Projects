## Unix Shell Lab

#### Files:

Makefile	- Compiles shell program and runs the tests  
README		- This file  
tsh.c		  - The shell program  
tshref		- The reference shell binary.

#### The files used to test my shell:
sdriver.pl	- The trace-driven shell driver  
trace*.txt	- The 15 trace files that control the shell driver  
tshref.out 	- Example output of the reference shell on all 15 traces

#### C programs that are called by the trace files:
myspin.c	   - Takes argument <n> and spins for <n> seconds  
mysplit.c	   - Forks a child that spins for <n> seconds  
mystop.c     - Spins for <n> seconds and sends SIGTSTP to itself  
myint.c       - Spins for <n> seconds and sends SIGINT to itself

