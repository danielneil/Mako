# Mako

Uses NiFi to download historical financial data from various sources.

It can be used to synchronise data for the [Shark Algorithmic Trading Platform](https://github.com/danielneil/Shark).

# Instructions 

<details>
<summary>System Requirements</summary>
<br>
  
| Operating System | CPU  | RAM | DISK |
| ------------- | ------------- | ------------- | ------------- |
| Rocky Linux 8+         | 4 CPU   | 4 GB | 80 GB  |
  
</details>


## Setup

<details>
<summary>System Installation</summary>
<br>
  
1. Prepare a vanilla Rocky Linux (server instance) with VirtualBox ([help](https://kifarunix.com/install-rocky-linux-8-on-virtualbox/)).

2. Install ansible ([help](https://www.how2shout.com/linux/how-to-install-ansible-on-rocky-linux-8-or-almalinux/)).

3. Install Git ([help](https://tastethelinux.com/2021/08/06/how-to-install-git-on-rocky-linux-8-ec2-aws/)).

4. Open a terminal, and run:
```
git clone https://github.com/danielneil/Mako.git && cd Mako && ./build.sh
```
5. Navigate to https://nifi-server:8080/nifi. 
