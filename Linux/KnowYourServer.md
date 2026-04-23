
 ## The basics

 - Accessing the servers/VMs:

When you want to "login" to a server running Linux Operating system (henceforth referred as Linux Machine), you use a SSH client such as putty, or Windows Terminal or any other tool. The authentication is generally done with the help of SSH Keys. Someone with admin rights have to copy your public key into the server and then you can do the password-less login. More on it later.

- Navigating around the computer. You enter a command into the SSH-Client (henceforth called as terminal for simplicity) and the command is sent to the linux machine and output displayed on the terminal. For instance let's assume we are connected to the linux machine called as web-server-01. Now, let's run our first command
`whoami` and hit enter. The output will be the name of the user with which you logged into the machine. 

<!-- Insert Image of the command and output -->

Now let's do our nexc command. Type in `last`



### The Prompt:
When you open a terminal session on your local machine (running Linux or Windows Subsystem for Linux) or connected to a remote machine with SSH, the first thing you would see is a prompt

![alt text](../.resources/prompt.png)




## Navigation 

```bash
pwd
```
