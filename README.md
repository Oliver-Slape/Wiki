# Wiki
## Debugging
### Definition
#### Debugging is the proccess of finding and resolving defects or problems within the program that prevent correct operation of computer software or systems.
### Incremental Debugging
#### Develop the program incrementally, and test it often, after adding each piece of code. It is likely that if there is an error, it occurs in the last piece of code that you wrote.  With incremental program development, the last portion of code is small; the search for bugs is therefore limited to small code fragments. 
### Instrument program to log information
#### Typically, print statements are inserted to keep check of outputs and inputs. Althought printed information is effective, it can also become difficult to inspect when the volume of logged data becomes huge. In those cases, automated scripts may be needed to sift through the data and report the relevant parts in a more compact format. 
### Use debuggers
#### if a debugger is avaliable, it can replace the manual instrumentation using print statements. Setting breakpoints in the program, stepping into and over functions, watching programs expressions, and instpecting the memory contents at selected points during the execution will give all the needed run-time information without generating large, hard to read log files. 
### Backtracking
#### One option is to start from the point where the problem occured and go back through the code to see how that might have happened. 
