#0x05. Processes and signals
	Resources;
		https://intranet.alxswe.com/rltoken/zh33PXDR6w_qyu7zXUezmw
		https://intranet.alxswe.com/rltoken/px2TdWSjVO8i9SB5gHchAw
		https://intranet.alxswe.com/rltoken/qQSGz9CN52PVF3IPCuaRiw
			https://intranet.alxswe.com/rltoken/XlYrlghzNZ6Z1cbI_IPaiA
	h2 man or help:
		https://intranet.alxswe.com/projects/255#:~:text=ps,trap
.h1 Write a Bash script that displays its own PID.
.h1 Write a Bash script that displays a list of currently running processes.
	#h3Requirements:



Must show all processes, for all users, including those which might not have a TTY

Display in a user-oriented format

Show process hierarchy.
.h2 Bash script that displays lines containing the bash word, thus allowing you to easily get the PID of your Bash process.
	.h3 Requirements:
		.You cannot use pgrep
		.The third line of your script must be # shellcheck disable=SC2009 (for more info about ignoring shellcheck error here)
			https://intranet.alxswe.com/rltoken/vErRT8QGU2bwJ6FLvPLzxw
		.h4Bash script that displays the PID, along with the process name, of processes whose name contain the word bash.
		Requirements:



You cannot use ps
		Here we can see that:



For the first iteration: bash PID is 4404 and that the 3-show_your_bash_pid_made_easy script PID is 4555

For the second iteration: bash PID is 4404 and that the 3-show_your_bash_pid_made_easy script PID is 4557
  h4#Bash script that displays To infinity and beyond indefinitely.



Requirements:



In between each iteration of the loop, add a sleep 2
