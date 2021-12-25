# venvwrapper #

Convenience wrapper scripts for using the python3 "venv" virtual environments.

## source mkvenv <projectName> ##
1. Creates a new folder named "projectName" in the default venv projects folder (by default that will be $HOME/venv_projects)

2. Creates a sub-folder within projectName called ".venv" which is populated with all the virtual environment infrastructure.

3. Changes current directory to the new project and activates the virtual environment.


## source workon [<projectName>] ##
1. When invoked WITHOUT specifying the <projectName> parameter the result is a list of existing project names.

2. When invoked WITH the <projectName> parameter it changes the current directory to that project and activates the virtual environment.

## source rmvenv <projectName> [--remove-project] ##
1. Deactivates and removed the specified projects virtual environment infrastructure.

2. If the "--remove-project" flag is also specified then the complete project directory (including any source files) is also deleted.

