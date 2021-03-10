# Error Handling & Debugging

![](https://0701.static.prezi.com/preview/v2/h3j5rflrkheepc5js3m7tae7e76jc3sachvcdoaizecfr3dnitcq_3_0.png)

### we will discuss how to handle exceptions in JSP. When you are writing a JSP code, you might make coding errors which can occur at any part of the code.
There may occur the following type of errors in your JSP code

+ Checked exceptions

*A checked exception is an exception that is typically a user error or a problem that cannot be foreseen by the programmer. For example, if a file is to be opened, but the file cannot be found, an exception occurs. 
These exceptions cannot simply be ignored at the time of compilation*

+ Runtime exceptions

*A runtime exception is an exception that probably could have been avoided by the programmer. 
As opposed to the checked exceptions, runtime exceptions are ignored at the time of compliation.*

+ Errors

*These are not exceptions at all, but problems that arise beyond the control of the user or the programmer. 
Errors are typically ignored in your code because you can rarely do anything about an error. For example, if a stack overflow occurs, an error will arise.
They are also ignored at the time of compilation.*

We will further discuss ways to handle run time exception/error occuring in your JSP code.

+ Using Exception Object

*The exception object is an instance of a subclass of Throwable (e.g., java.lang. NullPointerException) and is only available in error pages. 

+ Using JSTL Tags for Error Page

+ Using Try..
Catch Block
If you want to handle errors within the same page and want to take some action instead of firing an error page, you can make use of the try....catch block

![](https://jesusheredia.info/sites/default/files/styles/teaser/public/field/image/error.jpg?itok=VBKQsAHS)


Refranse [link 1](https://www.tutorialspoint.com/jsp/jsp_exception_handling.htm)
