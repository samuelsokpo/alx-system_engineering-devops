# :gear: 0x0B. SSH :gear:
 
## Background Context

Along with this project, you have been attributed an Ubuntu server, living in a datacenter far far away. Like level 2 of the application process, you will connect using ssh. But contrary to level 2, you will not connect using a password but an RSA key. We’ve configured your server with the public key you created in the first task of a previous project shared in your intranet profile.

You can access your server information in the my servers section of the intranet, each line with contains the IP and username you should use to connect via ssh.

Note: Your server is configured with an Ubuntu 16.04 LTS environment. You do not need to create a new virtual machine. If you decide you want to upgrade to Ubuntu 16.04, make sure to create a new VM. Do not attempt to upgrade your current Ubuntu 14.04 environment as that will inevitably be messy and can break things. Note that if you switch, none of your files and environment settings will be available and anything you need will have to be reinstalled or migrated.

## Resources
**Read or watch:**

- What is a (physical) server - text
- What is a (physical) server - video
- SSH essentials
- SSH Config File
- Public Key Authentication for SSH
- How Secure Shell Works
-SSH Crash Course (Long, but highly informative. Watch this if configuring SSH is still confusing. It may be helpful to watch at x1.25 speed or above.)

**For reference:**

- Understanding the SSH Encryption and Connection Process
- Secure Shell Wiki
- IETF RFC 4251 (Description of the SSH Protocol)
- Internet Engineering Task Force
- Request for Comments

**man or help:**

- ssh
- ssh-keygen
- env


### General
- What is a server
- Where servers usually live
- What is SSH
- How to create an SSH RSA key pair
- How to connect to a remote host using an SSH RSA key pair
- The advantage of using #!/usr/bin/env bash instead of /bin/bash

## Requirements :triangular_ruler:

### General

- Allowed editors: vi, vim, emacs
- All your files will be interpreted on Ubuntu 16.04 LTS
- All your files should end with a new line
- A README.md file, at the root of the folder of the project, is mandatory
- All your Bash script files must be executable
- The first line of all your Bash scripts should be exactly #!/usr/bin/env bash
- The second line of all your Bash scripts should be a comment explaining what is the script doing

## Your servers
**Name**	    **Username**    	**IP**	       **State**
~~~
1544-web-01	     ubuntu	     35.243.226.232	    running	     Soft reboot	    Hard reboot	     Ask a new server
~~~

## Author :book:
Roberto Palacios [Twitter](https://twitter.com/robpalacios11) | [GitHub](https://github.com/robpalacios1)
