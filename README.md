# Wiki
## Debugging
### Definition
#### Debugging is the proccess of finding and resolving defects or problems within the program that prevent correct operation of computer software or systems.
### Incremental Debugging
#### Develop the program incrementally, and test it often, after adding each piece of code. It is likely that if there is an error, it occurs in the last piece of code that you wrote.  With incremental program development, the last portion of code is small; the search for bugs is therefore limited to small code fragments. 
### Instrument program to log information
#### Typically, print statements are inserted to keep check of outputs and inputs. Althought printed information is effective, it can also become difficult to inspect when the volume of logged data becomes huge. In those cases, automated scripts may be needed to sift through the data and report the relevant parts in a more compact format. 
### Use debuggers
#### If a debugger is avaliable, it can replace the manual instrumentation using print statements. Setting breakpoints in the program, stepping into and over functions, watching programs expressions, and instpecting the memory contents at selected points during the execution and will give all the needed run-time information without generating large, hard to read log files. 
### Backtracking
#### One option is to start from the point where the problem occured and go back through the code to see how that might have happened. 
### Adding security
#### Debugging allows the creator to analyse the security of the program through testing, typically in log information. 
### Robustness 
#### Debugging can add robustness to a program. This can be from something such as user entries; if a user inputs something that the program did not expect or understand it will either crash or throw back an error if it cannot handle it. If the program can handle it the incorrect feedback will be given. This will generally be found in debugging and testing thus improving the robustness of the program.
### IDE VS Text Editor
#### Using an IDE adds extra Debugging options as they will generally have intergrated options already included. Depending on the IDE or language used they can have error logs and console outputs to show where and when errors have occured and why it has appeared. Compared to a Text Editor everything has to be done manually. This can be done through Incremental or Instrument Debugging taking more of the users time to implement and use these thus making an IDE much preffered.  

## From code to execution
### Preperation
#### Before any of the code can be created there needs to be a clear deffinition of the requirements, this would have been agreed with and delibereated with the client in an intial meeting or over several. 
### Language
#### Before any programming takes place an language need to be chosen to make the program (this can differ depending on what you want the program to do). 
### Text editor or IDE
#### Once the language has been chosen an evironemnt of which to program the code is needed. This is down to preference or compatability with the language. Some IDE's do not support all languages however they come with added bonuses which will be discussed in the next step. Text editors can support all languages.
### Complier or Interpreter
#### Based on the language you are using the code needs to be either Complied then Interpreted or just Interpreted into computer language (Binary) so that it can be exectuted. Most IDE's come with a Compiler or Interpreter built in. 
### Executable
#### All complied languages are in computer language as a package meaning they can be saved as a file in computer language. However interpreted languages are run line by line into computer language rather then as a package and cannot be saved as a computer language file unless they are converted to a seperate language. Computer language files are called executables. 

## Intergrated Development Environmnet (IDE)
#### An IDE is a development environment that is designed to maximise programmer prouctivity by providing tight-knit components with similar user interfaces. IDE's present a single program in which all development is done. 
### Common Features
#### An IDE commonly has an Source Code editor, Build automation tools, Debugger, Intelligent code completiion and Compiling. The Source Code Editor allows the user to access the base code of the program and all other code linked to the program allowing the user to edit, adapt and check the code. It also allows other feature such as code highlighting, syntax hints and much more. Build automation tools help the user in building the program by doing parts of it for them. This can be changing source code into extecutables through packaging, compiling or linking the code into a usable form. Compiling is a form of Build automation. IDE Debugging we have already touched on and can be seen above in the Debugging section. 

## Text Editor
#### A text editor is a type of program used for editing plain text files.

## Text Editor VS IDE
#### A text editor does not have the extra functionality that an IDE has. The text editor purely writes code with no hints or highlights. It also does not include the common features found in IDE's such as a Debugger or Compiler. Once a program has been written in a text editor everything else has to be done seperatly in the process of code to execution. Additionally, IDE's generally have extra functionality to help the user. This ranges from code navigation to spell checking, error checking, navigation and mainly and most helpful debugging. A lot of time is spent on debugging as it is a majour part of making any program. Having it intergrated into an IDE's saves a lot of time and is much more efficient compared to ways it can be acomplished using a Text Editor. Overal IDE's have extra functionality designed to help users be more efficicent and work easier. 

## Coding standards in teams
#### Having a coding standard in a team is majorly crutial as it allows for a consice understanding of the code through commenting, a clear format and structure through naming of variables, the positioning of syntax, indentation of blocks and layout of parentheses. All of this allows for the team and the individual to easily read and understand each others work.
