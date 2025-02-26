Download link :https://programming.engineering/product/lab-10-csc1310-heap-student-heap-prioritized-by-max-gpa/


# LAB-10-CSC1310-heap-student-heap-prioritized-by-max-GPA-
LAB 10 / CSC1310 heap student heap (prioritized by max GPA)
Step One – Read the Provided Code
You are provided with a Student class (Student.h). Read through this class to become familiar with the private & public members.

You are provided with an ArrayMaxHeap folder which has the sample program that implemented a max heap.

Step Two – Write a Student Heap class
Create a Heap class (call it Heap.h).

Refer to the sample ArrayMaxHeap program for an example of these functions.

However, do NOT make this a template class!

Private Members
Student* items; – this will be the heap array name
integer for heap_size and capacity
swap function
parent function
left function
right function
isLeaf function
heapRebuild function
Public Members
Heap constructor
Heap destructor
isEmpty function
getNumberOfNodes function
getHeight function
insert function
remove function
Step Three – write a driver program to use your Max Heap
Your main function in Driver.cpp should do the following:

Create a 50-bucket Heap object.
Create 10 Student objects with the given data:
GPA

NAME

MAJOR

2.6

Cosette Mealbone

HPC

4.0

April Crockett

CSSC

3.8

Beatrix Longbottom

CYBERSECURITY

3.9

Blaire Strange

DATA SCIENCE

2.9

Cybil Lidscrew

CSSC

1.4

Coco Mobo

DATA SCIENCE

3.2

Alabama Joebob

CSSC

3.6

Diem Carpefat

HPC

3.9

Chichi Musicpaper

CSSC

2.7

Bentlee Caryellow

CYBERSECURITY

 

Insert each of the 10 Student objects into the Max Heap.
Write a loop that will continue to run until the Heap is empty.
Inside the loop you should:
Print out the number of nodes (call getNumberOfNodes Heap function)
Print out the height of the heap (call getHeight Heap function)
Remove the student with the highest GPA (call remove Heap function) and then print out this Student that was removed (which should be the student with the highest GPA out of the students left in the heap).
What to turn in
Place Driver.cpp, Heap.h, & Student.h in a zipped folder and upload to ilearn submission folder.




Sample Output
Student Max Heap:

Number of nodes: 10

Height: 4

GPA: 4, NAME: April Crockett, MAJOR: CSSC

Number of nodes: 9

Height: 4

GPA: 3.9, NAME: Blaire Strange, MAJOR: DATA SCIENCE

Number of nodes: 8

Height: 4

GPA: 3.9, NAME: Chichi Musicpaper, MAJOR: CSSC

Number of nodes: 7

Height: 3

GPA: 3.8, NAME: Beatrix Longbottom, MAJOR: CYBERSECURITY

Number of nodes: 6

Height: 3

GPA: 3.6, NAME: Diem Carpefat, MAJOR: HPC

Number of nodes: 5

Height: 3

GPA: 3.2, NAME: Alabama Joebob, MAJOR: CSSC

Number of nodes: 4

Height: 3

GPA: 2.9, NAME: Cybil Lidscrew, MAJOR: CSSC

Number of nodes: 3

Height: 2

GPA: 2.7, NAME: Bentlee Caryellow, MAJOR: CYBERSECURITY

Number of nodes: 2

Height: 2

GPA: 2.6, NAME: Cosette Mealbone, MAJOR: HPC

Number of nodes: 1

Height: 1

GPA: 1.4, NAME: Coco Mobo, MAJOR: DATA SCIENCE
