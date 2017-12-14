# git-updater
This script will update all of your git repos. The script will use an external file called .git-directories which will hold the full path directories

# Usage
To properly use this program, create a hidden file called '.git-directories'. In this file will include the full path directories to each github repo. Please make sure each directory is seperated by a new line when inserting new ones.

/path/to/directory/first

/path/to/directory/second

# Running the script
When you run the script, an array is loaded based on the file holding the directories and a prompt asks you to select which folder you want updated. All selections are number based and a response must be an integer. Once a directory (or all of the directories) are chosen, then the script will go into each directory and update the git repository.
