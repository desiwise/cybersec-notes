# LINUX NOTES


## Moving Around
pwd -> prints where I am (e.g /home/username)
ls -> lists visible files and folders
ls -la -> lists everything, including hidden files, with details
cd /etc -> go into /etc
cd ~ -> go back to my home folder
cd lab -> go into the lab folder

## Files and Folders
mkdir lab -> make a folder
touch a.txt -> create an empty file
echo "hello kali" > a.txt -> write text into a file
cat a.txt -> show a file's contents
cp a.txt b.txt -> copy a file
mv b.txt c.txt -> move or rename a file
rm c.txt -> delete a file (permanent, no recycle bin)

## Reading and Searching
cat /etc/os-release -> system info, includes Kali GNU/Linux
head -5 /etc/passwd -> first 5 lines of the user list
grep root /etc/passwd -> only the lines containing "root"
whoami -> my username
id -> my uid, gid and groups

## Users (from /etc/passwd)
usr/sbin/nologin -> account cannot log in (normal for service accounts)
UID 0 -> root (full admin)
UID under 1000 -> system accounts
UID 1000+ -> normal users

## Permissions
ls -l file -> shows permissions (owner, group, others)
chmod 600 file -> only owner can read/write
chmod 644 file -> owner read/write, others read only
r=4 w=2 x=1 -> add them up for each group

## Shortcuts
CTRL+C -> stops the running command (shows ^C)
CTRL+Shift+C / V -> copy / paste in the terminal


### End
