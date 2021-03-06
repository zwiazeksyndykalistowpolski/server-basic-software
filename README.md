Basic software
==============

Basic administration tools such as monitoring shell commands,
package managers, git, networking tools, docker.

Compatibility:
- Debian
- Ubuntu Server 

Variables
---------

```yamlex

#
# Python's setuptools package name
#
setuptools_pkg_name: "python-setuptools"

#
# Python's package manager package name
#
python_pip_pkg_name: "python-pip"

#
# Installs a fresh docker and docker-compose from get.docker.com
#
docker: yes

#
# Schedule a clean up of unused docker images?
#
docker_schedule_clean_up: yes

#
# APT packages
#
apt_packages:
    - git
    - htop
    - iotop
    - iftop
    - iptraf
    - telnet
    - zsh
    - mc
    - python-pip
    - python-requests
    - python-yaml
    - python-jsonschema
    - python-docopt
    - python-texttable
    - traceroute
    - ctop
```
