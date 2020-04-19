# CSE 316  Operating Systems

Question Assigned:
Consider a scheduling approach which is non pre-emptive similar to shortest job next in nature. The priority of each job is dependent on its estimated run time, and also the amount of time it has spent waiting. Jobs gain higher priority the longer they wait, which prevents indefinite postponement. The jobs that have spent a long time waiting compete against those estimated to have short run times. The priority can be computed as : Priority = 1+ Waiting time / Estimated run time Write a program to implement such an algorithm. 
Using the data given below compute the waiting time and turnaround time for each process and average waiting time and average turnaround time.
 
#S.no	   Process	   Arrival Time	   Burst Time

1           P1               0                20
2           P2               5		      36
3           P3              13                19
4           P4              17                42
