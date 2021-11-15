These are two scripts I use to convert files with CRLF (Windows) to LF (Unix).

They work in place from the command line:

``fixascii <name-of-file>``

to convert one file.

``fixallascii``

to walk the entire directory tree and convert all the files.

As the name inplies it works with ASCII text but it also works with UTF-8.

It does require the utility programs zip and unzip to be installed and available.
