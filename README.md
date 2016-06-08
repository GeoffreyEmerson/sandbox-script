# Sandbox script

This is a bash script to quickly make a sandbox for testing HTML, CSS, or JavaScript. It will create a directory with a custom name, generate a basic html scaffold, css file, and JS file. It will then start a live-server of the sandbox and open those three files in a new Atom window (assuming you have live-server and Atom available form the terminal).

### Installation instructions

1. Copy the 'sb' file or clone this repo to a convenient location. I suggest using '.bin' in your home directory. The command ends up being this: `git clone git@github.com:GeoffreyEmerson/sandbox-script.git ~/.bin`
2. Navigate in the terminal to where you saved the script. E.g. `cd ~/.bin`
3. Make the script executable with this command: `chmod 711 sb`
4. Add the directory to your executable path. You'll have to dig into your .bash_profile and add this line: `export PATH=$PATH:/Users/<your user name>/.bin` or wherever you saved the script.

### Usage

$ `sb mySandboxName`

This script will make your sandbox directory in the current working directory.

##### Feedback welcome.
