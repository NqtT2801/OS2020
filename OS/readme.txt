In this labwork, we understand we have to create C program in order to implement command syntax and run it in Terminal.
However, we don't actual get the idea of some function in that program, so we copied your program and try to run it. 
-We met no problem with running 1 command (ex: ls, cd, ps -ef)
-Run 2 command, we typied "ps -ef | grep firefox", then it ran, but the loop did't continue. After following your instructions, we added close(p[0]) and close(p[1]), it worked perfectly! 
-Approach higher level with multiple command, we ran "ps -ef | grep firefox | wc -l", the some error occured but we can't fix it.