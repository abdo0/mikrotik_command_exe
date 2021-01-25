# mikrotik_command_exe
A simplify command script to execute Mikrotik router command through SSH in Linux terminal by passing arguments to it.

First, you need to install ``sshpass`` in your environment.

For Debian based:
```
$ sudo apt install sshpass
```
In RedHat/CentOS based systems:
```
# yum install sshpass
# dnf install sshpass    [On Fedora 22+ versions]
```
Make sure to that your script is executable by type the command:
```
chmod +x mikrotik.sh
```
To run the sciprt you should pass all data in terminal:
```
./mikrotik.sh <username> <password> <host> <command> 
```
