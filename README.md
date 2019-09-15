# User-designed-Hash-Map-in-C

This project implements hash map in C language. This may be used as user defined data structure in programs of C.
It supports following operations of Hash map:
#### Insert
#### Delete
#### Search
#### Update
#### Resize

The implementation uses open addressing/Closed hashing and double hashing to handle the collisions.

## How to Run

You'll need to link everything together with your compilation command. When the executable is run, whatever is in int main in main.c will be run. 
Here is the command that I am using to compile the code:

cc main.c hash_table.c prime.c -o ht

This will produce an executable called ht which you can run.
