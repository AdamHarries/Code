#A Simple "little man computer" simulator

this is a simple implementation, in c, of the "little man computer" model.
(see http://en.wikipedia.org/wiki/Little_man_computer)

##Compiling and running

to run the program with a file of LMC instructions call the program as follows:
	
	lmc.exe instructions_file
	
to compile the program run the following instructions:

standard:

	gcc lmc.c -o lmc -Wall

minimal:

	gcc lmc_minimal.c -o lmc_m -Wall

##Further info

There are two versions of the simulator here, the standard (lmc.c) and the minimal version (lmc_minimal.c).
The minimal version has less verbose commenting, and outputs less while the program is running, and without delays. This makes it faster, but less information about the running of the program is exposed to the user, making the standard version better for learning (about the running, and the structure of the program), but the minimal version better for running an actual program.


##File breakdown

code files:

*	lmc.c - standard version
*	lmc_minimal.c - minimal version

instruction files:

*	addition.txt - instructions to add two user inputted numbers
*	difference.txt - finds the difference bettween two user inputted numbers
*	loop.txt - counts down to 0 from a user inputted number

binaries are included without warranty in the "bin" folder
	