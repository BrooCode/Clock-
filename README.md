# CPP-Projects
Clock Using CPP Program

:All you have to know about this program:

1.<windows.h> is windows special header file for c/c++  programming languages which contains declarations for all of the functions in the Windows API.
All the various function declared in windows is defined.

2.system("cls") : In compilers like- Turbo C or Borland C, the statement clrscr() clears the output screen. But, in GNU based MinGW compilers the clrscr() statement is not supported because, clrscr () is not a part of the standard C library. So, to achieve this task in MinGW compilers, we use the system (“cls") statement. Anything inside the brackets of system () is directly sent to the command prompt of Windows. So, if you write system (“cls"), the program sends the cls command to Windows command prompt directly. And in response to the cls command, the Windows command prompt clears the output screen of the program.

3.Sleep() : inside paranthesis we write seconds in seconds
 The sleep () function causes the program or the process in which it is called, to suspend its execution temporarily for a period of time in seconds specified by the function parameter. Execution is suspended until the requested time is elapsed or a signal or an interrupt is delivered to the function.
suppose we write
{ 
cout<<"hello";
sleep(10);
cout<<"world";
}
here compiler write hello and the wait for 10 seconds and then write world.
   
    
