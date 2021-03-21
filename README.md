# Mako

Uses NiFi to download historical financial data from various sources.

It can be used to synchronise data for the [Shark Algorithmic Trading Platform](https://github.com/danielneil/Shark).

# Setup Instructions

1. Prepare a vanilla Debian Server with VirtualBox ([help](https://linuxhint.com/install_debian10_virtualbox/)).

2. Install ansible ([help](https://linuxhint.com/install_ansible_debian10/)).

3. Install Git ([help](https://linuxhint.com/install_git_debian_10/)).

4. Open a terminal, and run:
```
git clone https://github.com/danielneil/Mako.git && cd Mako && ./build.sh

# The build takes about 5 mins.
```
5. Navigate to https://nifi-server:8080/nifi. 
