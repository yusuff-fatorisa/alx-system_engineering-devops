## `0x05-processes_and_signals`

![Process and Signals Illustration](https://www.bogotobogo.com/Linux/images/process/ProcessState.png)

![Process And Signals Illustration](https://ssup2.github.io/images/theory_analysis/Linux_Signal_Signal_Handler/Linux_Signal_Handler_Process.PNG)


This repository contains tasks and projects on `Processes and signals` as related to `System Devops`

## `FILES`

The files contained in this repository includes

#### `README.md`
  - This file contains all the necessary information as regards to this repository and its contents.

#### `0-what-is-my-pid`
  - This file contains a `Bash Script` that displays its own process ID `PID`.

#### `1-list_your_processes`
  - This file contains a `Bash Script` that displays a list of currently running processes.

#### `2-show_your_bash_pid`
  - This file contains a `Bash Script` that displays lines containing the `bash` word, allowing to easily get the `PID` of the `Bash Process`.

#### `3-show_your_bash_pid_made_easy`
  - This file contains a `Bash Script` that displays the `PID`, along with the process name, of processes whose name contain the word `bash`.

#### `4-to_infinity_and_beyond`
  - This file contains a `Bash Script` that displays `To infinity and beyond` indefinitely.

#### `5-dont_stop_me_now`
  - This file contains a bash script that stops `4-to_infinity_and_beyond` process using `kill` command.

#### `6-stop_me_if_you_can`
  - This file contains a `Bash Script` that stops `4-to_infinity_and_beyond`.

#### `7-highlander`
  - This file contains a `Bash Script` that displays `To infinity and beyond` indefinitely. with a `sleep 2` in between each iteration, `I am invincible!!!` when receiving a `SIGTERM` signal.

#### `8-beheaded_process`
  - This file contains a `Bash Script` that kills the process `7-highlander`.
