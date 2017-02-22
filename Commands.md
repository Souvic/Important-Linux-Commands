To connect: ssh -i <key> username@server
Single file transfer : scp <source> <destination>
Multiple files transfer in form of directory: scp -r <source> <destination>
-v for verbose
-i <key> for identity via key
ls -1| wc -l  for number of files
Check regex also in linux as all these can be   further  customized  according to the name of the files or extension
ps -ef | grep splinter for listing out all processes that uses something with "splinter" in some part of their name
yum install screen
screen
run command
ctrl+A+D to detach
screen -r to re-attach
ctrl+D to kill.
simple ones : mkdir, vim(to quit :q), cp <src> <dest>, sudo su, su <username>
