# WSL Autostart
Support for starting the Linux services in Windows Subsystem for Linux (WSL) on Windows startup.

Adapted from  [troytse's `wsl-autostart`][troytse].


## Getting Started

1. Clone this repository: `git clone https://github.com/extrange/wsl-autostart`
2. Modify `commands.txt` to the commands you would like to execute in WSL. Note: The commands will run as the default user, **not** `root`.
3. Open Task Scheduler, and create a new task to run `start.vbs`.
  - If you would like the task to run when the computer is turned on, regardless of user login, ensure 'Run whether user is logged on or not' is ticked and the trigger is set to 'At system startup'.



[troytse]: https://github.com/troytse/wsl-autostart