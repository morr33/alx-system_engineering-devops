##SSH Project

###Description
This project is part of the DevOps curriculum and focuses on SSH (Secure Shell) usage and configuration. 
The goal is to connect to a remote server using an RSA key pair and understand key concepts related to servers and SSH.

##Tasks
###Task 0: Use a Private Key
Write a Bash script that uses ssh to connect to your server using the private key ~/.ssh/school with the user ubuntu. The script should only use single-character flags for ssh, and you are not allowed to use -l. Passphrase protection for the private key is not required.

##Task 1: Create an SSH Key Pair
Write a Bash script that creates an RSA key pair. The private key should be named school, have a key length of 4096 bits, and be protected by the passphrase "betty".

##Task 2: Client Configuration File
Configure your local SSH client using an SSH configuration file. The configuration should use the private key ~/.ssh/school and refuse authentication using a password.

##Task 3: Let Me In!
Add an SSH public key to your server to allow connecting using the ubuntu user.

##Task 4: Client Configuration File (w/ Puppet)
Use Puppet to configure the client SSH configuration file. Set up the configuration to use the private key ~/.ssh/school and refuse authentication using a password.



