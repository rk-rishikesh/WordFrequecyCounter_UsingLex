# WordFrequecyCounter_UsingLex
This lex program finds the term frequencies of all the words in the document. It makes use of Linked List data structure to maintain the count and finally displays them.

To run the program on windows, follow the following steps to install lex in your device.

Step 1: Download setup file for flex and bison from given link
        1. Install Flex: http://gnuwin32.sourceforge.net/packages/flex.htm

NOTE: Install flex in C:\GnuWin32 (do not use the default path)

Step 2: Download setup file for C
        https://sourceforge.net/projects/orwelldevcpp/
        Click on download

NOTE: Install in C:\Dev-Cpp

Step 3: Add to PATH variable
        Add the following to the path variable:
        C:\GnuWin32\bin
        C:\Dev-Cpp\MinGW64\bin
        C:\Dev-Cpp\MinGW64\libexec\gcc\x86_64-w64-mingw32\4.9.2
        C:\Dev-Cpp\MinGW64\x86_64-w64-mingw32\bin
        OR
        According to your machine installation the bin folder, version folder.

Follow the following steps to run the program

        1.Open command prompt: type cmd
  
  2. Change directory to folder where you have saved the lex file ( having .l extension)
  
  3. Run flex: flex count.l
  
  4. Then run c: gcc lex.yy.c
  
  5. To run exe: type a.exe and hit enter
