 Ansible role to install obs-studio on Debian
-----------------------------------------------
[![Build Status](https://travis-ci.org/DO1JLR/role_obs-studio.svg?branch=master)](https://travis-ci.org/DO1JLR/role_obs-studio)

This ansible role compiles obs-studio on debian 9.

Information about compiling comes from the official obs compile instructions (in the wiki).

Please have a look into ``defaults/main.yml`` to know what you can modify.

> The reason for this role is, that we choose debian as productive system for the video streaming setup from [toolbox bodensee](https://toolbox-bodensee.de). But debian 9 dosn't come with a modern version of obs-studio. We choose to keep our OS choise and compile obs by our self.

 Tasks during the playbook:
-------------------
During the playbook you need to install obs-studio by hand. 
The playbook will pause and promt you the command you need to enter.

If you now an other solution for this, please feel free to contact us by comming to the toolbox and talking about or opening an issue or pull-request!
 

