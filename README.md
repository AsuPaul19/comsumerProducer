# CSC 415 - Project 3 - Producer Consumer

## Student Name : Paul Asu

## Student ID : 920-164-164

## Build Instructions
make pandc

## Run Instructions
./pandc nb np nc x pTime cTime

for example: ./pandc 7 6 3 14 1 1

Project Description:
Implemented Producers and Consumer threads with a bounded buffer queue of N elements

Producer thread will  Enqueue X different numbers onto the queue  and wait for Ptime cycles in between each
call to Enqueue. Each Consumer thread will Dequeue P*X/C items from the queue  and wait for Ctime cycles
in between each call to Dequeue. The main program creates and initialize the Bounded Buffer Queue, print a
timestamp, spawn off C consumer threads & P producer threads, wait for all of the threads to finish and
then print off another timestamp & the duration of execution.
