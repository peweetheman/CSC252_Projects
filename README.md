# CSC252_Projects
This repository includes the projects completed for the CSC 252 Computer Organization course at the University of Rochester.

<p align="center">
<img src="http://www.cb-india.com/images/detailed/4/computer-systems-a-programmer-s-perspective-original-imaerfy3utyzgzpx.jpeg"
     alt="fsdasfdaaaaaaaaaaaaaaaaaaaaaaaaaafsdafsdafsadsafdfdsafsad"
     height="400" width="300">
</p>

The projects included (1) recreating a dynamic memory allocator for C (implementing algorithms for malloc() and free()), (2) creating a simple Unix shell, (3) using spatial and temporal cache locality to optimize code, (4) understanding and implementing buffer overflow attacks, and (5) stepping through and debugging assembly code.

(1) Creating the dynamic memory allocator in the <a href="https://github.com/peweetheman/CSC252_Projects/tree/master/malloc-lab">Malloc Lab</a> involved allocating and deallocating memory blocks apropriately and tracking which memory spots were vacant/occupied. Furthermore, it required doing this allocation process efficiently and without causing memory fragmentation.

(2) The <a href="https://github.com/peweetheman/CSC252_Projects/tree/master/unix-shell-lab">Unix Shell Lab</a> involved writing background methods that the unix shell runs (eg parsing input, tracking processes, implementing fg and bg methods, catching signals with SIGSTOP, SIGCHILD) A handout was provided with skeleton code for the unix shell.

(3) The <a href="https://github.com/peweetheman/CSC252_Projects/tree/master/cache-optimization-lab">Cache Optimization Lab</a> involved using loop unrolling, blocking, and other cache optimization techniques to minimize the number of CPE (cycles per element; a measure of computer time).
     
(4) The <a href="https://github.com/peweetheman/CSC252_Projects/tree/master/buffer-overflow-lab">Buffer Overflow Lab</a> involved writing code to do buffer overflow attacks in order to get a very detailed understanding of how the stack and heap interact and when things can go wrong.

(5) The <a href="(5) The <a href="https://github.com/peweetheman/CSC252_Projects/tree/master/assembly-bomb-lab">Assembly Bomb Lab</a> involved stepping through the assembly code with the GNU debugger to understand a C program and discover the seed string that would prevent the call to an explode() method that would "explode the bomb."

