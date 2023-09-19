| Command   | Explanation                                                                                                        |
|-----------|--------------------------------------------------------------------------------------------------------------------|
| man       | 1. Displays the manual or documentation for a command.                                                             |
|           | 2. Provides detailed information on command usage and options.                                                      |
| ls        | 1. Lists files and directories in the current directory.                                                            |
|           | 2. Can display various file attributes such as permissions and timestamps.                                          |
| cd        | 1. Changes the current working directory.                                                                          |
|           | 2. Allows navigation between different directories in the filesystem.                                                |
| pwd       | 1. Prints the current working directory.                                                                           |
|           | 2. Useful for verifying your current location in the filesystem.                                                     |
| mkdir     | 1. Creates a new directory.                                                                                        |
|           | 2. Useful for organizing files and creating directory structures.                                                     |
| rmdir     | 1. Removes an empty directory.                                                                                     |
|           | 2. Only works if the directory contains no files or subdirectories.                                                 |
| mv        | 1. Moves or renames files and directories.                                                                         |
|           | 2. Can also be used for moving files to different locations.                                                          |
| cp        | 1. Copies files or directories.                                                                                    |
|           | 2. Useful for duplicating files or creating backups.                                                                 |
| open      | 1. Opens files or directories using their default applications.                                                      |
|           | 2. Works primarily in graphical user interfaces.                                                                     |
| touch     | 1. Creates an empty file or updates the timestamp of an existing file.                                               |
|           | 2. Useful for creating placeholder files.                                                                           |
| find      | 1. Searches for files and directories in a specified location.                                                        |
|           | 2. Can be used with various criteria like name, type, or size.                                                        |
| ln        | 1. Creates links to files or directories.                                                                           |
|           | 2. Symbolic links (symlinks) and hard links provide different behaviors.                                               |
| gzip      | 1. Compresses files using the GZIP compression algorithm.                                                             |
|           | 2. Reduces file size while preserving the original content.                                                           |
| gunzip    | 1. Decompresses GZIP-compressed files.                                                                             |
|           | 2. Restores the original file from its compressed form.                                                               |
| tar       | 1. Archives files and directories into a single file.                                                                |
|           | 2. Often used in combination with compression for backups and distribution.                                           |
| alias     | 1. Creates shortcuts or aliases for commands.                                                                       |
|           | 2. Simplifies long or complex command execution.                                                                      |
| cat       | 1. Concatenates and displays file contents.                                                                         |
|           | 2. Useful for viewing the content of text files.                                                                     |
| less      | 1. Displays file contents one screen at a time.                                                                     |
|           | 2. Allows scrolling and searching within large files.                                                                 |
| tail      | 1. Displays the end (tail) of a text file.                                                                          |
|           | 2. Often used for monitoring log files in real-time.                                                                 |
| wc        | 1. Counts the number of lines, words, and characters in a text file.                                                  |
|           | 2. Helpful for analyzing text data.                                                                                  |
| grep      | 1. Searches for text patterns in files.                                                                             |
|           | 2. Supports regular expressions for powerful text matching.                                                           |
| sort      | 1. Sorts lines of text files.                                                                                      |
|           | 2. Can be used to alphabetically or numerically order data.                                                           |
| uniq      | 1. Filters out duplicate lines from sorted text.                                                                     |
|           | 2. Useful for finding unique entries in data.                                                                        |
| diff      | 1. Compares the content of two files or directories.                                                                |
|           | 2. Highlights the differences between them.                                                                          |
| echo      | 1. Prints text or variables to the terminal.                                                                        |
|           | 2. Often used in scripts to display messages or variables.                                                            |
| chown     | 1. Changes the owner of files or directories.                                                                       |
|           | 2. Useful for managing file ownership and permissions.                                                               |
| chmod     | 1. Modifies file permissions (mode).                                                                               |
|           | 2. Controls who can read, write, or execute a file.                                                                   |
| umask     | 1. Sets the default permissions mask for newly created files and directories.                                       |
|           | 2. Influences the default permissions applied when creating files.                                                   |
| du        | 1. Displays disk usage for files and directories.                                                                   |
|           | 2. Helps identify space-consuming files and folders.                                                                 |
| df        | 1. Shows disk space usage for file systems.                                                                         |
|           | 2. Provides information on available and used disk space.                                                             |
| basename  | 1. Strips directory and suffix from a file path.                                                                    |
|           | 2. Useful in scripts for extracting filenames from paths.                                                             |
| dirname   | 1. Retrieves the directory portion of a file path.                                                                   |
|           | 2. Helpful for working with file paths in scripts.                                                                   |
| ps        | 1. Lists running processes.                                                                                        |
|           | 2. Displays information such as process IDs and resource usage.                                                        |
| top       | 1. Provides real-time system resource and process monitoring.                                                        |
|           | 2. Allows tracking of CPU, memory, and other system metrics.                                                           |
| kill      | 1. Sends signals to terminate processes.                                                                            |
|           | 2. Can be used to gracefully stop or forcefully kill processes.                                                        |
| killall   | 1. Kills processes by name.                                                                                        |
|           | 2. Terminates multiple processes with the same name.                                                                  |
| jobs      | 1. Lists background jobs in the current shell session.                                                              |
|           | 2. Useful for managing and controlling background processes.                                                           |
| bg        | 1. Puts a job or process in the background.                                                                        |
|           | 2. Allows a process to continue running while you work in the shell.                                                  |
| fg        | 1. Brings a background job or process to the foreground.                                                             |
|           | 2. Resumes interaction with a backgrounded process.                                                                   |
| type      | 1. Indicates how a command is interpreted by the shell.                                                              |
|           | 2. Shows whether a command is a built-in, alias, or external program.                                                 |
| which     | 1. Locates the executable file associated with a command.                                                             |
|           | 2. Helps identify the full path of a command in the system.                                                           |
| nohup     | 1. Runs a command immune to hangups (HUP signals).                                                                  |
|           | 2. Useful for running processes that should persist even after logging out.                                          |
| xargs     | 1. Executes a command with arguments from standard input.                                                            |
|           | 2. Facilitates running commands on multiple files or input lines.                                                      |
| vim       | 1. Opens the Vim text editor.                                                                                      |
|           | 2. Offers powerful text editing features and modes.                                                                   |
| emacs     | 1. Launches the Emacs text editor.                                                                                 |
|           | 2. Known for its extensibility and various editing modes.                                                              |
| nano      | 1. Opens the Nano text editor.                                                                                     |
|           | 2. Provides a simple and user-friendly interface for text editing.                                                      |
| whoami    | 1. Prints the username of the current user.                                                                         |
|           | 2. Useful for verifying your identity in scripts or commands.                                                           |
| who       | 1. Displays a list of currently logged-in users.                                                                    |
|           | 2. Shows information about user sessions on the system.                                                               |
| su        | 1. Switches user accounts.                                                                                         |
|           | 2. Allows you to become another user, typically the superuser (root).                                                  |
| sudo      | 1. Executes commands with superuser (root) privileges.                                                               |
|           | 2. Enables authorized users to perform administrative tasks.                                                            |
| passwd    | 1. Changes the password for a user account.                                                                         |
|           | 2. Provides a secure way to update user passwords.                                                                   |
| ping      | 1. Sends ICMP echo requests to test network connectivity.                                                            |
|           | 2. Checks if a remote host is reachable and measures response time.                                                     |
| traceroute | 1. Traces the route packets take to reach a destination.                                                             |
|           | 2. Shows the network path and delays between your computer and a target host.                                         |
| clear     | 1. Clears the terminal screen.                                                                                     |
|           | 2. Provides a clean workspace by removing previous output.                                                              |
| history   | 1. Displays a list of previously executed commands.                                                                 |
|           | 2. Helps you recall and repeat previous actions in the terminal.                                                       |
| export    | 1. Sets environment variables.                                                                                     |
|           | 2. Makes variables available to child processes and shell sessions.                                                    |
| crontab   | 1. Manages scheduled tasks using the cron daemon.                                                                   |
|           | 2. Allows you to automate repetitive tasks at specific times or intervals.                                             |
| uname     | 1. Retrieves system information.                                                                                   |
|           | 2. Displays details about the operating system and kernel.                                                             |
| env       | 1. Lists environment variables.                                                                                    |
|           | 2. Shows the current environment settings for the shell session.                                                       |
| printenv  | 1. Prints the values of environment variables.                                                                     |
|           | 2. Specifically focuses on displaying the values of environment variables.                                             |
