Here's the write of my BANDIT OverTheWire wargame
The pattern of my write up will be as follows:
   1. What I Learned 
   2. How it was done
   3. Password I found i this for next level

*BANDIT LEVEL 0*
   1. Learned How to connect to the server using SSH
   2.  i) used the command "ssh bandit0@bandit.labs.overthewire.org -p 2220" 
        ii) Entered the Password the password ' bandit0 '
   3.Password for Level 1 is : ZjLjTmM6FvvyRnrb2rfNWOZOTa6ip5If

*BANDIT LEVEL 1*
   1.  Listing files and reading a simple text file.
   2. i) Used ' ls ' to list files
       ii)Used 'cat' to read the content of file
   3. Password for Level 2 is : 263JGJPfgU6LtdEvgfWU1XP5yac29mFx


*BANDIT LEVEL 2*
  1.Learned How to find and locate Hidden Files
  2. i) Used 'ls -al' to list all files
     ii)Used 'cat .hidden' to read the hidden file
  3.Password for Level 3 is: MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx


*BANDIT LEVEL 3*
   1.Understanding file names with spaces
   2.Used 'cat  "spaces in this filename" ' to read the file with spaces in its name 
   3.Password for Level 4 is :2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ 



*BANDIT LEVEL 4*
  1.Finding files with specific properties (e.g. file size )
  2.i)Used 'file ./' to identify file types
     ii)Used 'cat ./-file' to read a file with dash in its name
 3. Password  for Level 5  is : 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
 

*BANDIT LEVEL 5*
 1. searching a file from directories with some specification given in questions
 2. i) used command 'file' to locate the file in '/inhere'
    ii) used ' cat ./inhere/maybehere07/.file2 ' to read correct file
 3. Password for Level 6 is :  HWasnPhtq9AVKe0dmk45nxy20cvUa6EG


*BANDIT LEVEL 6*
 1. using ' find ' to  specify some criteria like size , user , group
 2. i)Used ' find / -user bandit7 -group bandit6 -size 33c ' to locate the file.
    ii)Used ' cat ./var/lib/dpkg/info/bandit7.password ' to read the content.
 3.Password  for Level 7 is : morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj

*BANDIT LEVEL 7*
 1. Learned command 'grep' for files within pattern
 2. i) Used 'grep millionth data.txt' to find the file which contains the word "millionth"
 3. Password for level 8 is : dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc

*BANDIT LEVEL 8*
 1. Learned string command to find unique strings in file 
 2. i) Used ' sort data.txt | uniq -u 'to find the unique line.
 3. Password for Level 9 is : 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM

*BANDIT LEVEL 9*
 1. Learned Finding specific patterns or certain character in a file
 2. Used 'strings data.txt | grep =' to find the password with equal signs in the file .
 3. Password for Level 10 is : FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey

*BANDIT LEVEL 10*
 1.Learned How to decompress the file and How to decode the Encoded files.
 2.Used 'cat data.txt | base64 --decode ' to decode the encoded file to retrieve the Password .
 3.Password for Level 11 is : dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr

*BANDIT LEVEL 11*
 1.In this level I learned how to find content which all lowercase (a-z) and uppercase (A-Z) letters have been 
    rotated by some ' x ' positions.
 2.Used ' cat data.txt | tr a-zA-Z n-za-mN-ZA-M ' to find the exact words which has been rotated . 
 3.Password for Level 12 is : 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4

*BANDIT LEVEL 12*
 1. Learned How to handle compressed file with multiple layers .
 2. Used 'tar' , 'gzip' , 'bzip2' ,  ' xxd r ' commands to extract multiple layers of multiple compressed files 
     until final password is  received .
 3. Password for Level 13 is : FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn

*BANDIT LEVEL 13*
 1. Utilized 'ssh' with private keys.
 2. ' ssh -i sshkey.private bandit14@localhost ' to connect to the next level using private SSH Key.
 3. Password for Level 14 is : MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS

*BANDIT LEVEL 14*
 1.Learned a new command ' nc ' or  which used for network communication 
 2.Used ' nc ' localhost 30000 ' to connect to the server and to retrieve the password
 3.Password for Level 15 is : 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo

*BANDIT LEVEL 15*
 1. Learned ' SSL ' for establishing an encrypted link between server and client  and ' OPENSSL ' is a 
    command-line tool for using SSL
 2.Used " openssl s_client -connect localhost:30001 " to connect to the server securely and retrieve the 
    password 
 3.Password for Level 16 is : kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx

*BANDIT LEVEL 16*
 1.Learned ' nmap ' which uses to scan the network and discover what services each host is operating
 2.i) Used ' nmap -A localhost -p 31000-32000 ' which connects to a port within range of 31000-32000
  ii)  Used ' openssl s_client -connect localhost:31790 ' to connect to that port.
  iii) Now created a new temporary directory and Used it to ssh into the next level
  iv) Used 'ssh -i bandit17key.private bandit17@localhost ' to connect to the server to next level and ' cat 
       /etc/bandit_pass/bandit17  'Find out the actual password for bandit17
 3. Password for Level 17 is : EReVavePLFHtFlFsjn3hyzMlvSuSAcRD


*BANDIT LEVEL 17*
 1.Learned a new command called ' diff ' which compares 2 files line by line and shows the differences
 2.Used the command ' diff passwords.old passwords.new ' for getting password for next level which is in password.new
 3.Password for Level 18 is : x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO

*BANDIT LEVEL 18*
 1.The password for the next level is stored in a file readme in the homedirectory.as mentioned in question it says ' ByeBye ' when trying to log into bandit18
 2.SO i passed the command ' cat readme ' directly to ssh command to bypass the issue.
 3.Password for Level 19 is : cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8

*BANDIT LEVEL 19*
 1.To gain acces to next level , I used ' setuid ' binary in the home directory.Execused it without arguements to find out how to use it as mentioned in question.
 2.i)Used ' ./bandit20-do '  to use the setuid binary
  ii)Used '  ./bandit20-do cat /etc/bandit_pass/bandit20  ' to get password for next level.
 3.Password for Level 20 is : 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO

*BANDIT LEVEL 20*
 1.To solve this Level I opened two terminals. one to run setuid command and other to start a network daemon to which setuid will connect.
 2.i)In terminal 1 I used ' nc -lp 31337 < /etc/bandit_pass/bandit20 ' to connect to localhost on port that I specify.It reads a line of text from connection and compares 
     it to password from previous level , If password is correct , it will give password for next level.
  ii)In terminal 2 I used ' ./suconnect 31337 ' to connect and get password which will appear in terminal 1.
 3.Password for Level 21 is : EeoULMCra2q0dSkYj561DX7s1CpBuOBt

*BANDIT LEVEL 21*
 1.A program is running automatically at regular intervals from cron, the time-based job scheduler.
 2.i)First listed all files in /etc/cron.d/ using command ' ls -la /etc/cron.d/ '
  ii)Used ' cat /etc/cron.d/cronjob_bandit22 ' to read the cronjob_bandit22.sh script executed by cron.





Passwords For all level from 0-21 listed below :


level 1→2  -- 263JGJPfgU6LtdEvgfWU1XP5yac29mFx
level 2 →3 – MNk8KNH3Usiio41PRUEoDFPqfxLPlSmx
level 3 → 4 -- 2WmrDFRmJIq3IPxneAaMGhap0pFhF3NJ 
level 4 → 5 -- 4oQYVPkxZOOEOO5pTW81FB8j8lxXGUQw
level 5 → 6 – HWasnPhtq9AVKe0dmk45nxy20cvUa6EG
level 6 → 7 – morbNTDkSW6jIlUc0ymOdMaLnOlFVAaj
level 7 → 8 – dfwvzFQi4mU0wfNbFOe9RoWskMLg7eEc
level 8 → 9 – 4CKMh1JI91bUIZZPXDqGanal4xvAg0JM
level 9 → 10 – FGUW5ilLVJrxX9kMYMmlN4MgbpfMiqey
level 10 → 11 -- dtR173fZKb0RRsDFSGsg2RWnpNVj3qRr
level 11→ 12 -- 7x16WNeHIi5YkIhWsfFIqoognUTyj9Q4
level 12 → 13 -- FO5dwFsc0cbaIiH0h8J2eUks2vdTDwAn
level 13 → 14 -- MU4VWeTyJk8ROof1qqmcBPaLh7lDCPvS
level 14 → 15 – 8xCjnmgoKbGLhHFAZlGE5Tmu4M2tKJQo
level 15 → 16 -- kSkvUpMQ7lBYyCM4GBPvCvT1BfWRy0Dx
level 16 → 17 -- EReVavePLFHtFlFsjn3hyzMlvSuSAcRD
level 17 → 18 -- x2gLTTjFwMOhQ8oWNbMN362QKxfRqGlO
level 18 → 19 -- cGWpMaKXVwDUNgPAVJbWYuGHVn9zl3j8
level 19 → 20 -- 0qXahG8ZjOVMN9Ghs7iOWsCfZyXOUbYO
level 20 → 21 – EeoULMCra2q0dSkYj561DX7s1CpBuOBt
