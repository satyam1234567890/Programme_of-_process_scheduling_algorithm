# Programme_of-_process_scheduling_algorithm
programme in c++ with proper comment and refer by javatpoint
FCFS Scheduling:-

First come first serve (FCFS) scheduling algorithm simply schedules the jobs according to their arrival time. The job which comes first in the ready queue will get the CPU first. The lesser the arrival time of the job, the sooner will the job get the CPU. FCFS scheduling may cause the problem of starvation if the burst time of the first process is the longest among all the jobs. 

The FCFS scheduling algorithm. In the Following schedule, there are 5 processes with process ID P0, P1, P2, P3 and P4. P0 arrives at time 0, P1 at time 1, P2 at time 2, P3 arrives at time 3 and Process P4 arrives at time 4 in the ready queue. The processes and their respective Arrival and Burst time are given in the following table. 

    Turn Around Time = Completion Time - Arrival Time   
        Waiting Time = Turnaround time - Burst Time   
        
Process ID 	Arrival Time 	Burst Time 	Completion Time 	Turn Around Time 	Waiting Time
0 	0 	2 	2 	2 	0
1 	1 	6 	8 	7 	1
2 	2 	4 	12 	8 	4
3 	3 	9 	21 	18 	9
4 	4 	12 	33 	29 	17

               Avg Waiting Time=31/5
