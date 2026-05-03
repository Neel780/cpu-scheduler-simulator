# CPU Scheduling Simulator

A browser-based simulator implementing four CPU scheduling algorithms 
relevant to mobile OS resource management research:

- **FCFS** — First Come First Served (baseline comparison)
- **SJF** — Shortest Job First (minimizes average wait time)
- **Round Robin** — Time-quantum based (basis of Android's CFS scheduler)
- **Priority Scheduling** — Used in Android foreground app boosting

## Why this exists
Built as research preparation for studying adaptive resource optimization 
on entry-level mobile hardware. Demonstrates tradeoffs in waiting time, 
turnaround time, CPU utilization, and throughput across scheduling strategies.
