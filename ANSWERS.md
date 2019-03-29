**1. List all of the main states a process may be in at any point in time on a standard Unix system. Briefly explain what each of these states means.**
A process is generally ready, running, or waiting. Ready means that the process is queued up and available to run when requested. Running means the process is in action, and waiting means that a process is in the state of waiting on its child process to run before continuing to exiting. 


**2. What is a zombie process?**
A zombie process is a process that is not killed off after it finishes running. 


**3. How does a zombie process get created? How does one get destroyed?**
A zombie process is created when wait() isn't called for a parent's child. It generally is destroyed by the parent. If the parent process ends and the child isn't waited on, the child will be inherited by the next process up. 


**4. What are some of the benefits of working in a compiled language versus a non-compiled language? More specifically, what benefits are there to be had from taking the extra time to compile our code?**
Compiled languages are usually faster than non-compiled languages because the code doesn't have to be interpreted and they are compiled directly into assembly language. 


