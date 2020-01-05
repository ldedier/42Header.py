# 42Header.py

Useful class to generate 42 norm's proof C files.

## Usage

* This class needs a  **login** and a **mail address**, replace this class' attributes with your owns !

## Functions

* HeaderWriter.openFile("Sample.c") will return the fd of Sample.c in **writing mode** after adding the 42Header.
* HeaderWriter.writeHeader(fd, "Sample.c") will add the 42Header to fd, considering that fd is the file descriptor of Sample.c in **writing mode**.
