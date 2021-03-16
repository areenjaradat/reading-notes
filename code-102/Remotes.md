# Version Control

types of Version Control:

1. Local Version Control
2. Centralized Version Control
3. Distributed Version Control

# what is Git?

Git is a DVCS that stores data in a file system made up of snapshots.
Each time you save a changed version of your project — called commit — Git creates
a snapshot of the file and stores a reference to it.mostly relies on local operations
because most necessary information can be found in local resources. This allows for
process expediency because a project’s history resides on the local disk, eliminating 
the need to fetch history information from the server, and allowing one to continue
work on a project even when not online or on a VPN.

## Graphical Clients

Git includes inherent Graphical User Interface (GUI) tools. However, users can also utilize third-party tools created for particular platforms.

### Configuration of Variables

An inherent Git tool called git config allows the setting of configuration variables that control aspects of Git’s operation and look.

### Identity

After installing Git, users should immediately set the user name and email address, which will be used for every Git commit.

### Check Settings

To check settings, use the git config --list command.

### Importing

To import an existing project or directory into Git, follow these steps using the Terminal or Command Line:

Switch to the target project’s directory
Example:
$ cd test (cd = change directory)
Use the git init command
$ git init

To start tracking these repository files, perform an initial commit by typing the following:
$ git add *.c
$ git add LICENSE
$ git commit -m “any message here”

### Cloning

By cloning the file, you have copied all versions of all files for a project. This command leads
to the creation of a directory called “test,” with an initialized .git directory inside it, which
has copies of all versions of all files for the specified project. The command also automatically 
checks out — or retrieves for editing — a copy of the newest version of the project.
