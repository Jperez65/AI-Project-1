# Assingment 1: Problem 3

On the assingment 1 problem #3 it requested to write a programing file that function as a dijktra algorithm 

## Compile and Run

To compile file you must have python 3.8.5 ver installed in your system environment or use any other IDE programs. 
After that you must go to the directory where the program is located and write 


> python Project.py


to your console terminal

## Running the program

Before running the program you must have a text file with the name "sample.txt"in the same directory before running it. The text file content must follow the format of three number seperated by a single space. Example:

> 2 3 0
> 
> 3 4 2

After you run it the program will output:

>Starting Vertex:

You will input here the starting vertex node where the uniform-cost search will be begin searching then it will output.

>Ending Vertex:

Again you will input the ending vertex node where the uniform-cost search will end when searching the path. 

After both vertex has been enter it will output the list of vertex it will be traveling from and arriving to with it cost output it on the way. After the loop it will finally output the total cost of the search found and then terminates the program. Example:

>vertex 2 to vertex 13, cost 3
>
>vertex 13 to vertex 5, cost 4
>
>vertex 5 to vertex 3, cost 6
>
>Total cost: 13
>
>Ending of program

#### Condition- scenario

###### If one of the input does not exist in the text file

>Starting vertex: 2
>
>Ending vertex: 30
>
>Graph does not have one of the vertex you inputed
>
>Ending of program
'''
###### if the starting vertex has no edges


>Starting vertex: 2
>
>Ending vertex: 15
>
>Initial vertex has no outgoing edge
>
>Total cost: 0
>
>Ending of program

###### if the ending vertex has no edges going to it


>Starting vertex: 2
>
>Ending vertex: 15
>
>Goal vertex does not have an in going edges
>
>Ending of program


### Author
Josue Perez







