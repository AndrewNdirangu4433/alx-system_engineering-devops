	0x05-processes_and_signals
	==========================

	# This is a directory for tasks in alx-system_engineering-devops/0x05-processes_and_signals
	# Modules and tasks in this directory include:
		1. > 0-what-is-my-pid:
			Write a Bash script that displays its own PID.

		2. > 1-list_your_processes:
			Write a Bash script that displays a list of currently running processes.
				Requirements:
				-------------
					Must show all processes:
					(for all users, including those which might not have a TTY)
					Display in a user-oriented format.
					Show process hierarchy.

		3. > 2-show_your_bash_pid:
			Using your previous exercise command,
			write a Bash script that displays lines containing the bash word,
			thus allowing you to easily get the PID of your Bash process.
				Requirements:
				-------------
					You cannot use pgrep.
					The third line of your script must be :
					<# shellcheck disable=SC2009>

		4. > 3-show_your_bash_pid_made_easy:
			Write a Bash script that displays the PID:
			along with the process name,
			of processes whose name contain the word bash.
				Requirements:
				-------------
					You cannot use ps
