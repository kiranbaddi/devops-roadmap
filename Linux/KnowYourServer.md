
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

THe prompt generally gives you three pieces of info. On most systems the prompt is of the below format: 

```bash
<username>@<hostname>:<current_directory> >
```
In the above pic, the username is `kiran` and the hostname (name of the computer) is `web-server-01` and the current directory is `~`

> ~ is representation of the Home directory of the user which is generally /home/<username>

When a user changes the directory, the prompt also changes. For instance if the user changes into /etc, the prompt looks like this : `kiran@web-server-01:/etc>`.
Notice the part after the colon, it says `/etc`

### Which Operating System are you logged in to ?

Let's say you are given access to a system and you are able to login to the machine without any other info (Metadata) of the machine. How do you know which operating system you are logged in? yes, Linux, but what is the distribution you loggedd in.

The easiest way to know that is with the command 

```bash
cat /etc/*se
```

![OS Info](../.resources/os-info.png)

> Every distribution has a file under /etc directory with the name os-release or release hence the wild card `*se`, you don't have to know the name of the directory.

## Navigation 

```bash
pwd
```


