# Main states

1.
Running = All of the resources are allocated to the CPU.

Runnable = The process is consuming resources, but it has no CPU; it has to wait for the CPU to be available to then switch to a running state.

Sleeping = Releases all CPU while it waits, when certain conditions are met, the CPU wakes up.

Stopped = Process is killed after entering an exit status or kill signal.

Zombie = A process that was remains in the operating system's process table; a process that has completed its execution, but still has entry in the process table

# What is Scheduler?

The scheduler is what gives system resources to various tasks performed on the OS, it accomplishes this with job queues.

# MLFQ vs Round-Robin

The MLFQ allows you to prioritize certain jobs; this in not functionallity that is found in the Round-Robin.
