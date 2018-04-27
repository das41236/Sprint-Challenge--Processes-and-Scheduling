1. 
Running: Process is currently running or about to be scheduled for runing.
Waiting: Process is waiting on an interrupt or an event to happen.
Stopped: Process is stopped.
Zombie: The process is dead, but is still in the list of processes and taking up memory space.

2.
A Process that gets created when the Parent process does not wait for the child to finish, if the child finishes after the parent then this process never gets terminated and remains in memory, but not running.

3.
The scheduler manages the priorities of each process and how much time they are given to execute in each processor cycle. It can create the effect of all processes running simultaneously.

4. 
MLFQ gives priority to the processes that are newly created, then lowers their priority if they are very compute intensive. This allows the processor to complete all the smaller processes very quickly while still taking the time to compute larger ones in the background.