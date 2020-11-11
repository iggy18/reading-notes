# reading and writing a file

- a file is a contiguous set of bytes used to store data.

- Files on most modern file systems are composed of three parts:

- **Header:** metadata about the contents of the file (file name, size, type, and so on)
- **Data:** contents of the file as written by the creator or editor
- **End of file `(EOF)`:** special character that indicates the end of the file

- file path is a string that represents the location of a file. 

- three major parts:
- *Folder* Path: the file folder location on the file system where subsequent folders are separated by a forward slash / `(Unix)` or backslash \ `(Windows)`
- *File Name:* the actual name of the file
- *Extension:* the end of the file path pre-pended with a period `(.)` used to indicate the file type

- The double-dot `(..)` can be chained together to traverse multiple directories above the current directory `(../../../)`.

### Line Endings
- Windows uses the `CR+LF` characters to indicate a new line, while Unix and the newer Mac versions use just the `LF` character.

### Character Encodings
- An encoding is a translation from byte data to human readable characters
- The two most common encodings are the ASCII and UNICODE Formats.

### opening and closing a file
- open a file with `open(path/to/file)`
- You should always make sure that an open file is properly closed.

- you should open and close a file in a try finally block.

- `reader = open('dog_breeds.txt')`
- `try:`
-    *file stuff*
- `finally:`
-    `reader.close()`


