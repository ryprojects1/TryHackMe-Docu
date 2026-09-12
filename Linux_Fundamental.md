### Room:Linux Fundamental Part 1 (9/9/2026)
whoami, tells you who you are on the system
echo, output text that you provided
ls, list out whats in the current folder
cd, change directory
cat, show content of a file
pwd, print the current directory you are in
find, search for files based on the name you provided. Example: find -name passwords.txt
grep, searches inside for text
&, runs the command and does not wait for it to be finised.
&&, runs both command but waits for the first to finish before going to the next instruction
>, redirect output. Operator will overwrite anything that exists in the file
>>, redirector does the same thing but doesn't overwrite

### Room: Linux Fundamentals Part 2(9/9/2026)
Learnt about SSH, 
ls -a, show hidden folders
ls --help, gives out a brief description of possible options that ls can used
touch, create file
mkdir, create a folder
cp, copy a file or folder
mv, move file or folder
rm, remove file or folder 
/etc, commonplace location where system and program files are stored
/var, stores data that services and applications write to or read often, like log files
/root, actual home, nothing else more to this folder
/tmp, store temporary files 
Permission Columns:Read (open the file), Write (make changes to the file), Execute (run the file, such as a script or application)
su, switch users
### Room: Linux Fundamentals Part 2(10/9/2026)
Nano, one of the terminal text editors
nano (filename), to create or edit a file using nano
VIM, a more advanced text editor
Wget, downloading files
scp (Secure copy), this command allows you to transfer files between two computers using the SSH protocol to provide both authentication and encryption.
Example:scp important.txt ubuntu@192.168.1.30:/home/ubuntu/transferred.txt
ps, provides a list of the running process like task manager
ps aux, to see the processes run by other users and those that don't run from a session 
kill, terminate processes
systemctl,  allows us to interact with the systemd process/daemon. Example: systemctl [option] [service]
the 5 options: Start, Stop, Enable, Disable, Status
fg, bring the background process back into use on the terminal
