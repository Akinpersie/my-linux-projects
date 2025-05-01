## Process Management

### Objective
- Learn how to manage processes in Linux, including starting, stopping, and monitoring processes.

### Steps
- Start a Background Process: Start a long-running process in the background (e.g., sleep).

>   sleep 300 &

![screenshot-1](backgroundprocesses.JPG)

- List Running Processes: List all running processes.

>   ps aux

![screenshot-2](runningprocesses.JPG)

- Kill a Process: Find the process ID (PID) of the sleep process and kill it.

>   ps aux | grep sleep

![screenshot-3](killaprocess.JPG)

- Monitor System Resources: Use top to monitor system resources.

> top

![screenshot-4](top.JPG)

- Change Process Priority: Start a new sleep process and change its priority using nice and renice.

> nice -n 10 sleep 300 &

![screenshot-5](nice.JPG)