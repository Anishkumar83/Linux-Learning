# Linux-Learning
Basic linux commands with example

What is UNIX?

    Multiuser & Multitasking: Unix allows multiple users to use the system at the same time and 
run multiple programs simultaneously without interfering with each other.

    Powerful Command-Line Interface: Unix is controlled mainly through commands, allowing
 users to manage files, processes, and system resources efficiently and combine commands to
 perform complex tasks.

    Stable & Portable: Unix is known for its stability and reliability, and it can run on different
 hardware platforms, making it ideal for servers and long-running systems.


Define Linux?

    Open source Operating system: Linux is free open source, which means anyone can view, modify,
 and distribute its source code.
    Unix-like and secure: Linux is based on Unix principles and provides strong security through 
user permissions,process isolation and access control.
    Widely Used and Flexible: Linux runs on everything from servers and cloud platforms to desktops,
 mobile devices, and embedded systems, making it highly flexible and reliable.

Linux Basic commands:

commands [options] [arguments]

pwd - present working directory

Change directories:
---------------------------------------------------------------------------------------------
cd folder_ name -it will move to the new file or directory

cd .. -> it denotes go back one folder

cd ~ -> it denotes home directory

Moving files commands:
------------------------------------------------------------------------------------------------
mv file_ name /path/to/destination -> basic move file to the destination

mv old-file-name new-file-name -> rename the file

mv -i -> Prompts before overwriting a file in the destination if a file with the same name exists.

mv -u -> move only if the source file is newer

mv -v -> verbose mode(show details of the moved files)

mv -f -> forces the moving operation

mv --backup -> Create a backup of the destination file if it exists

mv --no-clobber -> Prevents overwriting files in the destination if they already exist.

Creating files in Linux
--------------------------------------------------------------------------------------------------------
touch file-name -> it creates a empty file

cat > file-name     -> It creates a file and save the content in the file
[content to save]

nano file-name -> It creates a file if it is not exist and opens visual editor

vi/vim file-name -> It creates a file if it is not exist and opens visual editor.

Creating directories in linux
-------------------------------------------------------------------------------------------------------
mkdir -> it creates a directory

mkdir file1 file2 file3 -> it ceeates a multiple directories

mkdir -p parent/child/grandchild -> it creates a nested directories in a single command

Deleting directories in linux(no recycle bin once deleted files are permanently removed)
---------------------------------------------------------------------------------------------------------
rm files -> delete files

rm file1 file2 -> delete multiple files 

rmdir -> remove directories

rm -r dir -> we cannot delete directories which are all not empty for that we use this which is recursive deletion.

rm -rf -> force delete

Directory hierarchy overview
-----------------------------------------------------------------------------------------------------------
/: Root directory, the top level of the file system.
/home: User home directories.
/bin: Essential binary executables.
/sbin: System administration binaries.
/etc: Configuration files.
/var: Variable data (logs, spool files).
/usr: User programs and data.
/lib: Shared libraries.
/tmp: Temporary files.
/opt: Third-party applications.


