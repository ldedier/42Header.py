# 42Header.py
useful function to generate 42 norm's proof C files

## Usage

* The class needs a  **login** and a **mail address**, replace this class' attribute with your own !

## Functions

* HeaderWriter.openFile("Sample.c") will return the fd of Sample.c in **writing mode** after adding the 42Header
* HeaderWriter.writeHeader(fd) will add the 42Header to the fd 
