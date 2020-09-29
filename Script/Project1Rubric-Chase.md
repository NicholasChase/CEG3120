# Project 1:

## Score:
24.8 / 25

### Repository Layout (4 points total): 4 / 4
* Repo created & instructor added: 1 pt
* Resources page includes 1 or more sites / credits to project success: 1 pt
* README page includes description / usage of Project 1 script: 1 pt
* Script folder contains at least a script for the project: 1 pt

### Repository usage requirements (2 points total): 2 / 2
* Instructor can clone the repository and run the script: 1 pt
* At least one commit / push was made to the repository: 1 pt

### Script functionality requirements (19 points total): 16.3 / 19
1. PATH requirement (4 points total): 3.8 / 4
* Adds the path to the script(s) to the PATH via the `.profile`: .8 / 1
    * TODO: Need to add full path to `Scripts` to `PATH`
* Checks an existence condition (2 pt) of either:
    * checking if script directory is in path / exists
* Outputs message to user to `source .profile`: 1 pt

2. `motd` requirement (2 points total): 2/2
* Removes one or more default messages: 1 pt
* Adds one or more custom messages: 1 pt

3. `vim` requirement minimum expectations (3 pts total): 1/3
* Modifies `.vimrc`: 1 pt
* Adds plugin directory (2 pts) by either: TODO
    * Having the plugin in the repository and copying it for installation
    * Downloading / cloning the plugin to its installation location

4. `alias` requirement (6 points total): 5.5/6
* Adds aliases to `.bashrc`: 1 pt
* Checks existence of aliases before appending to `.bashrc`: 2 pts
* Aliases to add: 
    * `alias` called `aws-ssh` that contains command to ssh to system: 1 pt
    * second `alias` of choice: 1 pt
* Output message to user to `source .bashrc`: .5/1
    * TODO: looks like this got commented out

5. help option requirement (2 points total): 2/2
* Running command with at least one of `help` / `-help` / `h` / `-h` does a thing: 1 pt
* Output message of what the script does 1 pt

6. All requirements above are neatly wrapped up in functions: 2/2

### Extra Credit (10%) + 2.5 pts
* Created a menu for the script
   * https://www.shellscript.sh/tips/getopts/ 
   * Minimum of –i (dash i) for install & -h (dash h) for help / usage