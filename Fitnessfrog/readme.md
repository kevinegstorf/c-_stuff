when using Mac first install Mono

To compile use mcs:

```mcs hello.cs```

The compiler will create “hello.exe”, which you can run using:

```mono hello.exe```

to fire up charp console type:

``
charp
```

To compile the program with additional debugging information, use this command instead:

```
mcs -debug Program.cs
```
This creates a file called Program.exe.mdb in addition to Program.exe. The file contains additional information for the debugger to use.

To run the program with the debugger, run this command:

```
mono --debug Program.exe
```
Now error messages for exceptions will contain more detailed information such as the exact line of code that threw the exception.
