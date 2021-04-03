# Mako

Uses NiFi to download historical financial data from various sources.

It can be used to synchronise data for the [Shark Algorithmic Trading Platform](https://github.com/danielneil/Shark).

# Instructions 

<details>
<summary>System Requirements</summary>
<br>
  
| Operating System | CPU  | RAM | DISK |
| ------------- | ------------- | ------------- | ------------- |
| Debian GNU/Linux 10         | 4 CPU   | 8192 MB | 80 GB  |
  
</details>


## Setup

1. Prepare a vanilla Debian Server with VirtualBox ([help](https://linuxhint.com/install_debian10_virtualbox/)).

2. Install ansible ([help](https://linuxhint.com/install_ansible_debian10/)).

3. Install Git ([help](https://linuxhint.com/install_git_debian_10/)).

4. Open a terminal, and run:
```
git clone https://github.com/danielneil/Mako.git && cd Mako && ./build.sh
```
5. Navigate to https://nifi-server:8080/nifi. 
