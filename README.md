# how-to-install-c-and-c-plus-plus-compiler

## Steps for downloading mingw-w64 for c/c++ in windows:
+ Go to google and search for ```mingw-w64.org```.
+ Click on ```downloads``` which is left hand side of the page.
+ Under ```Pre-built toolchains and packages``` search for ```MSYS2``` and click on it.
+ After that search for ```MSYS2: Installation: GitHub``` and click on it.
+ Then under ```Installation``` click on ```msys2-x86_64-20210725.exe```.

## or you can click below link to go directly to installation page
<a href = "https://www.msys2.org/">Click me 😊</a>

+ After downloading install the downloaded file by double click on that file.
+ When the installation window opens click on ```Next Next ...``` then ```finish``` but before finish make sure that you had ☑️ ```Run MSYS2 64bit now```.
+ After that it pop-up a terminal,

## Run below code
+ In pop-up termainl type ```pacman -Syu``` for updating package database and base package.
+ After that close the terminal and search for ```MSYS2 MinGW 64-bit``` and open it.
+ Now run ```pacman -Su``` to update the rest of the base packages.
+ Then run ```pacman -Ss gcc``` for seeing all types of compilers
+ Search for 
```
mingw64/mingw-w64-x86_64-gcc 11.2.0-2 (mingw-w64-x86_64-toolchain) [installed]
    GNU Compiler Collection (C,C++,OpenMP) for MinGW-w64 
```

+ Now run ``` pacman -S mingw-w64-x86_64-gcc ``` for final installation.

## Run below code to check weather it is installed or not
+ For c compiler,
```
$ gcc --version

gcc.exe (Rev2, Built by MSYS2 project) 11.2.0
Copyright (C) 2021 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

+ For C++ compiler,
```
$ g++ --version
g++.exe (Rev2, Built by MSYS2 project) 11.2.0
Copyright (C) 2021 Free Software Foundation, Inc.
This is free software; see the source for copying conditions.  There is NO
warranty; not even for MERCHANTABILITY or FITNESS FOR A PARTICULAR PURPOSE.
```

## 🎉🎉Congratulation you had finally installed C/C++ compiler🎉🎉
