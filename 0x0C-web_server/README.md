# :gear:0x0C. Web server:gear:
 
**For this project, students are expected to look at these concepts:**

- DNS
- Web Server
- CI/CD
- Docker
- Web stack debugging
- DevOps
- System Administration
- Site Reliability Engineering


## Background Context

In this project, some of the tasks will be graded on 2 aspects:

1. Is your web-01 server configured according to requirements
2. Does your answer file contain a Bash script that automatically performs commands to configure an Ubuntu machine to fit requirements (meaning without any human intervention)

For example, if I need to create a file /tmp/test containing the string hello world and modify the configuration of Nginx to listen on port 8080 instead of 80, I can use emacs on my server to create the file and to modify the Nginx configuration file /etc/nginx/sites-enabled/default.

But my answer file would contain:
~~~
roberto@ubuntu cat 88-script_example
#!/usr/bin/env bash
# Configuring a server with specification XYZ
echo hello world > /tmp/test
sed -i 's/80/8080/g' /etc/nginx/sites-enabled/default
roberto@ubuntu
~~~
As you can tell, I am not using emacs to perform the task in my answer file. This exercise is aiming at training you on automating your work. If you can automate tasks that you do manually, you can then automate yourself out of repetitive tasks and focus your energy on something more interesting. For an SRE, that comes very handy when there are hundreds or thousands of servers to manage, the work cannot be only done manually. Note that the checker will execute your script as the root user, you do not need to use the sudo command.

Tips: to test your answer Bash script, feel free to reproduce the checker environment:

- start an ubuntu:16.04 Docker container
- run your script on it
- see how it behaves

Check out the Docker concept page for more info about how to manipulate containers.

## Resources
**Read or watch:**

- How the web works
- Nginx
- How to Configure Nginx
- Child process
- Root and sub domain
- HTTP requests
- HTTP redirection
- Not found HTTP response code
- Logs files on Linux

**For reference:**

- RFC 7231 (HTTP/1.1)
- RFC 7540 (HTTP/2)

**man or help:**

- scp
- curl


### General
- What is the main role of a web server
- What is a child process
- Why web servers usually have a parent process and child processes
- What are the main HTTP requests

### DNS
- What DNS stands for
- What is DNS main role

### DNS Record Types
- A
- CNAME
- TXT
- MX

## Requirements :triangular_ruler:

### General
- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- Your Bash script must pass Shellcheck (version 0.3.7) without any error
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Your servers
**Name**	      **Username**	        **IP**	         **State**
~~~
1544-web-01	       ubuntu	        35.243.226.232	      running	       Soft reboot	      Hard reboot	        Ask a new server
~~~

## Author :book:
Roberto Palacios [Twitter](https://twitter.com/robpalacios11) | [GitHub](https://github.com/robpalacios1)
