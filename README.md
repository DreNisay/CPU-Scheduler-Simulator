# CPU-Scheduler-Simulator
Developers: Chua, Mary Elizabeth E., Nisay, Deiondre Judd V.

In accordance to a course project of CMSC 125: Operating Systems

To simulate different preemptive scheduling algorithms such as Shortest-Job-First Scheduling, Priority Scheduling, and Round Robin Scheduling


Background of CPU Scheduling
When there are multiple processes in the queue, various scheduling techniques are used to choose which ones will run on the CPU. The following criteria are used to identify the optimum scheduling algorithm: minimum waiting time, minimum response time, and minimum turnaround time while optimizing CPU utilization.


According to the given machine problem, the different algorithms to simulate are:
1. Shortest-Job-First (SJF) – also known as shortest-next-CPU-burst algorithm, which gives priority to processes that have the smallest CPU burst. It can either be non-preemptive or preemptive. Preemptive SJF prioritizes the processes with the smallest remaining time as the processes are running.

2. Priority Scheduling (PS) – from its name, a process is given a rank or a priority value with the lowest set as the highest priority. If all processes arrive at the same time, no pre-emption occurs. But in the case where there are processes arriving at different times, the processes with higher priority will preempt any current running processes.

3. Round-Robin (RR) – algorithm where the processes are executed following the first-come first-serve basis but can only run within the set time quantum duration. Processes that will have a time burst of more than the time quantum will have to wait for the next round after all the processes are run within the set time quantum.
