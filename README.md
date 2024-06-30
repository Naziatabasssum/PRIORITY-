# PRIORITY-
Program Explanation

1. First, enter the total number of processes and store it in variable n.
2. After that, provide the burst time and priority and store it in variable b and p.
3. Finding out highest priority element and placing it at its desired position.
4. Sort the processes on the basis of the priority.
5. After that print the processed with their time stamp (starting time and ending time). Variable T stores the starting time of process.
6. In the end, print the waiting time and turnaround time for each process. Waiting time is the time spent in the ready queue, while turnaround time is the total time taken by process (burst time + waiting time).

Time Complexity: O(n*n)
Sorting takes time of the order of O(n*n), So time complexity is of the order of O(n*n).

Space Complexity: O(n)
Space is required to store burst time, arrival time and index, So space complexity is O(n).

Run Time Testcases
In this case, we enter “3” as the number of processes, and the burst time and priority value are “p1: 10 2”, “p2: 5 0”, and “p3: 8 1”.

Enter Number of Processes: 3
Enter Burst Time and Priority Value for Process 1: 10 2
Enter Burst Time and Priority Value for Process 2: 5 0
Enter Burst Time and Priority Value for Process 3: 8 1
Order of process Execution is
P1 is executed from 0 to 10
P3 is executed from 10 to 18
P2 is executed from 18 to 23
 
Process Id     Burst Time   Wait Time    TurnAround Time
    P1            10          0            10
    P3            8          10            18
    P2            5          18            23
