# BoyInTheBrowser

Build a website that:

Allows the user to submit a putative infected file and shows if it is infected or not
Allows the user to submit a surely infected file, plus the name of the malware
 

Build a web application that:

Reads the file in input per bytes and, if is a surely infected one, store the sequence of bytes, say, the first 20 bytes (signature) of the file, in a database
Reads the file in input per bytes and, if it is a putative infected file, searches within the file for one of the strings stored in the database
 

Build a MySQL database that:

Stores the information regarding the infected files in input, such as name of the malware (not the name of the file), the sequence of bytes, and...
