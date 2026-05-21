## The core components of Linux (kernel, user space, init/systemd)
## Kernel : 
kernel is the core of the operating system.
Linux is a kernel

## UserSpace:
Terminal is an application installed on the OS . Through which we type the command for the shell to interact with kernal and do the job,

## How processes are created and managed?
A program is just a file stored on disk.
A process is that program loaded into RAM and actively running.

| State | Meaning                                 |
| ----- | --------------------------------------- |
| `R`   | Running or ready to run                 |
| `S`   | Sleeping, waiting for event             |
| `D`   | Uninterruptible sleep, usually I/O wait |
| `T`   | Stopped/paused                          |
| `Z`   | Zombie process                          |
| `X`   | Dead process                            |


## What systemd does and why it matters
Systemd is the first process (pid=1) thats responsible to start all other processes

## List 5 commands you would use daily

cd 
ls
mkdir
touch
cat
