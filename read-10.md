# JS Debuggung

## Each time a script enters a new execution context, there are two phases 
of activity: 

1-PREPARE 

• The new scope is created 
• Variables, functions, and arguments are created 
• The value of the this keyword is determined 

2-EXECUTE 

• Now it can assign values to variables 
• Reference functions and run their code 
• Execute statements

## HOW TO DEAL WITH ERRORS

1: DEBUG THE SCRIPT TO FIX ERRORS 
  you will need to debug the code, track down the source of the error, 
and fix it. 


2:HANDLE ERRORS GRACEFULLY 

You can handle errors gracefully using try, catch, 
throw, and fina1ly statements.

If you understand execution contexts (which have two 
stages) and stacks, you are more likely to find the error 
in your code. 

Debugging is the process of finding errors. It involves a 
process of deduction. 

The console helps narrow down the area in which the 
error is located, so you can try to find the exact error. 

JavaScript has 7 different types of errors. Each creates 
its own error object, which can tell you its line number 
and gives a description of the error. 

If you know that you may get an error, you can handle 
it gracefully using the try, catch, finally statements. 
Use them to give your users helpful feedback.
