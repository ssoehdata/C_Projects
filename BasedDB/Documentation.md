#### include this????

Source environment: 
Linux Mint (Ubuntu) 21.2 x86_64
Kernel: 6.8.0.60 
Compiler(s): 
gcc - 11.4.0

###########

In place of comments throughout the source code, this document will include  explanatory notes on the project with references to specific features and implementations. 
#############################
Project Definition and Scope: 

The database (BASEDDB) will include Create, Read, Update, and Delete (CRUD) functionality for an 
employee database to track basic employee data as well as tracking hours worked. The database will
be a command line interface (cli) using posix shell commands and utilities.
#############################

Features:  File verification  (define and give examples of how this is done)



Project Organization: 

directory contents: 

include    - includes the header files for the project (parse.h, file.h, common.h)
bin         - where the generated binaries will be stored 
src         - where the source code files (main.c parse.c file.c)
obj         - stores the intermediate .o object files in the build process 
makefile  - used for the build process

get opt:  library for functionality used for the command 
            line implementation of command line arguments the database  will use. 
            This is included in the main.c src file. Command line flags such as -f  for a filename.


Command line Utility:

(include from main.c print_usage with explanations, flag usage etc )
- as well as the usage  message ( -n create new database, -f (required) path to database)
 etc

