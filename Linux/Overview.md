# Overview:

## What is Linux? 

Linux is not just an Operating System - it's an emotion, it is a way of Life. Sorry, I am supposed to teach you Linux not go into a monologue on how great Linux is! 
But yeah, it's the greatest Operating Sytem on Planet earth. No matter on which device you are reading this there must be linux involved somewhere in the path from the origin to you. 

Now to the technical part: As said above, Linux Operating System is the widely used operating system on Servers. Linux is a Free and Open Source Operating System. It is widely used as the server operating system. Even when you have to manage Docker containers or Kubernetes, there is Linux under the hood.

## Linux Vs Windows

- Windows Operating Systems including the server OSes come with a graphical user interface, where as servers running Linux only have a Command Line Interface (CLI) to work with.  [Linux can also be used very much as a Desktop Operating System on your personal desktops and laptops. In fact I have written this guide on my Thinkpad running [Debian](https://www.debian.org/)]

 ## Flavors of Linux

 Linux comes in different flavors. Since it's a Free and Open Source software - a lot of people have taken the codebase and added their own code on top of it and made it better and sometimes customized to some particular requirements. These flavors are known as `Distributions` or `distro` for short.

 ### Key distributions

 - Debian: A very stable and reliable linux distribution that is popular on both personal computers and servers.
 - Ubuntu: A derivate of Debian with it's own touch. Slightly higher usage than Debian on personal computers and servers. It's maintained by Canonical
 - RHEL: A very popular distribution for Enterprise servers is RedHat Enterprise Linux. It is managed by the company [RedHat Inc](https://redhat.com). RHEL is a commercial offering (paid). The 
 - Alpine: A light weight distribution that is popular in Container instances. Alpine contains only bare minimum software packages to keep the contianer images small and secure.    



 ## The basics

 - Accessing the servers/VMs:

When you want to "login" to a server running Linux Operating system (henceforth referred as Linux Machine), you use a SSH client such as putty, or Windows Terminal or any other tool. The authentication is generally done with the help of SSH Keys. Someone with admin rights have to copy your public key into the server and then you can do the password-less login. More on it later.

- Navigating around the computer. You enter a command into the SSH-Client (henceforth called as terminal for simplicity) and the command is sent to the linux machine and output displayed on the terminal. For instance let's assume we are connected to the linux machine called as web-server-01. Now, let's run our first command
`whoami` and hit enter. The output will be the name of the user with which you logged into the machine. 

<!-- Insert Image of the command and output -->

Now let's do our nexc command. Type in `last`



- File System

- Networking

- Process Management

- Service Management 

- Utilities
  - Search - find, grep
  - Text Manipulation: awk, cut, sed 
  - Network: ping, telnet, dig, curl, wget
