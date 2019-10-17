*Jan Kaufmann 3AHIF*
# System Calls
## Fork
Creates new process by duplicating the calling process the new process is called child process.

No arguments

### Fail
Fails when there is no memory to allocate.

## Stat
Returns information about a file from the path.

### Arguments
#### char* pathname
The file from where you want the information.

#### struct stat* statbuf
Return buffer

## Kill
Can be used to send a signal to any process

### Arguments
#### pid_t pid
Is the process ID, if it is 0 sig is sent to every process in the process group.

#### int sig
The signal to send to a process if 0 can be used to check if a process exists.

## mmap
### Arguments
