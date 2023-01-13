# C Learning Notes
Our objective is to get started with a most basic C code syntax

## getting over installation and typical beginner hitches
+ installing your compiler/ IDE/plugins etc, ; too varied not commented /not described
+ if you already have it installed and tested; fine; 
  +if not,you are better off using an online REPL
	+ example: https://www.tutorialspoint.com/online_c_compiler.php
+ try creating a hello world file/project/solution for and compile/run it 
> + void main () {printf("Hello world !");}
> + #include <stdio.h> at top of file, if the compiler complains that printf if not defined
+ if #include<stdio.h> is reported missing or flags some error, you will get warnings when you use printf
+ if libraries/SDKare installed 
	+ but not configured properly 
	+ sometimes you have to set environment vars
	+ you may end still end up getting errors. resolve them first.
  + if you cant resolve/fix these errors, and want to get going, again the solution is an online REPL
  + example: https://www.tutorialspoint.com/online_c_compiler.php
