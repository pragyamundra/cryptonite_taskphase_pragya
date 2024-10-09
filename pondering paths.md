## The ROOT
absolute path can be invoked by using the /pwn command as given in the challenge.
>
hacker@paths~the-root:~$ /pwn
BOOM!!!
Here is your flag:
**pwn.college{YW3q3t01bHZ_BN65JerIEJClwDm.dhzN5QDL3gDO0czW}**
## Program and Absolute paths
This challenge again requires us to execute it by invoking its absolute path
>
/challenge/run
Correct!!!
/challenge/run is an absolute path! Here is your flag:
> **pwn.college{sbkmjDvUks2oGeVomjZ-We5hAoy.dVDN1QDL3gDO0czW}**
## Position thy self
This challenge will require you to execute the /challenge/run program from a specific path which we need to cd into before
> /challenge/run
Incorrect...
You are not currently in the /proc/173/fd directory.
>
i ran this code to know the directory i need to be in 
>
then i used the cd command to get and then to obtain the flag
>cd /proc/173/fd
hacker@paths~position-thy-self:/proc/173/fd$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
**pwn.college{w7NsltlFm6xsUUnNVQHmh1oceei.dZDN1QDL3gDO0czW}**
## position elsewhere
>challenge/run
Incorrect...
You are not currently in the /var/log directory.
used this to know the directory
>cd /var/log
/var/log$ /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
**pwn.college{42Do9VqKF4FMigSlFxepkykQGHw.ddDN1QDL3gDO0czW}**
got the flag
## position yet elsewhere
did the same thing to find the driectory and the cd into it
>cd /sys
hacker@paths~position-yet-elsewhere:/sys$  /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
pwn.college{sdirncJlGqPN4h3tcLH6VZ1OEVU.dhDN1QDL3gDO0czW}
>cd /sys
hacker@paths~position-yet-elsewhere:/sys$  /challenge/run
Correct!!!
/challenge/run is an absolute path, invoked from the right directory!
Here is your flag:
**pwn.college{sdirncJlGqPN4h3tcLH6VZ1OEVU.dhDN1QDL3gDO0czW}**
## implicit relative paths from /

>hacker@paths~implicit-relative-paths-from-:~$ cd /
hacker@paths~implicit-relative-paths-from-:/$ challenge/run
Correct!!!
challenge/run is a relative path, invoked from the right directory!
Here is your flag:
**pwn.college{kAgMBgLn53GbMJoRDosvFB3bnUB.dlDN1QDL3gDO0czW}**
## explicit relative path from /
>hacker@paths~explicit-relative-paths-from-:~$ cd /
hacker@paths~explicit-relative-paths-from-:/$ ./challenge/run
Correct!!!
./challenge/run is a relative path, invoked from the right directory!
Here is your flag:
**pwn.college{0_1SmfWssQOzaE1db6bHgZRDtzc.dBTN1QDL3gDO0czW}**
## implicit relative path

>hacker@paths~implicit-relative-path:~$ cd /challenge
hacker@paths~implicit-relative-path:/challenge$ ./run
Correct!!!
./run is a relative path, invoked from the right directory!
Here is your flag:
**pwn.college{cV7lYQHDXLfCeVZzueU3mv8jl2g.dFTN1QDL3gDO0czW}**
## home sweet home
the program >/challange/run requires an argument that specifies the absolute path not more than three characters ..also wrote the file to a
>hacker@paths~home-sweet-home:~$ /challenge/run ~/a
Writing the file to /home/hacker/a!
... and reading it back to you:
**pwn.college{YH6Qc61IsGGXMgj8zqojDPW3Bnn.dNzM4QDL3gDO0czW}**







