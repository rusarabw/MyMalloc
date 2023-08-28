# MyMalloc

## Code that I wrote for the following assignment.

Implement a malloc-like memory allocation library in C.
1. Declare a global array of 25000 bytes.
2. You must implement a function that is like malloc(). Call it MyMalloc(). Its signature is similar to malloc(). You should also implement MyFree()
which has a signature and functionality that are similar to free(). Read the documentation on malloc() and free(). It would be a good idea to use
malloc and free before attempting to implement MyMalloc() and MyFree().
3. MyMalloc() allocates memory only from the previously mentioned array of 25000 bytes.
4. All the data structures that are required to manage the memory must also reside within the same array.
5. MyMalloc() and MyFree() must be in a file called mymalloc.c. You should also provide a suitable header file mymalloc.h.
6. Our test program contains the main() and it includes mymalloc.h. Do not include a main() in your mymalloc.c.
7. You cannot use malloc() and free() in your implementation of MyMalloc() and MyFree().

## How to setup your environment and Run the code

1. Download and install a [compiler](https://sourceforge.net/projects/mingw/).
2. Add the gcc path to the Environment Variables path. By default the gcc path on Windows is,
```
C:\MinGW\bin\gcc
```
3. Download and save the source files *mymalloc.c* and *mymalloc.h*.
4. Change the directory of the *cmd* into the source file's folder.
```
cd C:\example\path\
```
5. Compile the code using a test program.
```
gcc test.c mymalloc.c -o a.exe
```
6. Run the Code
```
a.exe
```
