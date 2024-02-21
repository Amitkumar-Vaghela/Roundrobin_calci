# Roundrobin_calci
A round-robin is a CPU scheduling algorithm that shares equal portions of resources in circular orders to each process and handles all processes without prioritization.


#Round Robin CPU Scheduling Algorithm

Step 1: Organize all processes according to their arrival time in the ready queue. The queue structure of the ready queue is based on the FIFO structure to execute all CPU processes.
Step 2: Now, we push the first process from the ready queue to execute its task for a fixed time, allocated by each process that arrives in the queue.
Step 3: If the process cannot complete their task within defined time interval or slots because it is stopped by another process that pushes from the ready queue to execute their task due to arrival time of the next process is reached. Therefore, CPU saved the previous state of the process, which helps to resume from the point where it is interrupted. (If the burst time of the process is left, push the process end of the ready queue).
Step 4: Similarly, the scheduler selects another process from the ready queue to execute its tasks. When a process finishes its task within time slots, the process will not go for further execution because the process's burst time is finished.
Step 5: Similarly, we repeat all the steps to execute the process until the work has finished.


#Characteristics of Round Robin

It is a pre-emptive algorithm.
It shares an equal time interval between all processes to complete their task.
It is a starvation free CPU scheduling algorithm. Hence it is known as the fairest and simple algorithm.


#The following are the important terms to find the Completion time, Turn Around Time (TAT), Response Time (RT) and Waiting Time (WT).

Completion Time: It defines the time when processes complete their execution.
Turn Around Time: It defines the time difference between the completion time (CT) and the arrival time (AT).
Turn Around Time (TAT) = Completion Time (CT) - Arrival Time (AT)
Waiting Time: It defines the total time between requesting action and acquiring the resource.
Waiting Time (WT) = Turn Around Time (TAT) - Burst Time (BT)
Response Time: It is the time that defines at which time the system response to a process.
