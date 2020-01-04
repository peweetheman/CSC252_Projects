# Performance Lab


kernels.c
	This is the file that I modified to optimize cache operations.

### Other files
driver.c
	This is the driver that tests the performance of all 
	of the versions of the rotate and smooth kernels 
	in your kernels.c file.

config.h
	This is a site-specific configuration file

defs.h
	Various definitions needed by kernels.c and driver.c

clock.{c,h}

fcyc.{c,h}
	These contain timing routines that measure the performance of the
	code by k-best measurement scheme using IA32 cycle counters.

Makefile:
	This is the makefile that builds the driver program.
