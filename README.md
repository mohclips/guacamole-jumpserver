# Intro

This git repository contains an Ansible role which creates an Apache Guacamole Server (HTML5 RDP/SSH Terminal Server).


# Usage


```defaults/guacamole.yml``` contains; 

As these are in the defaults folder, you can override them in your playbook.

* The passwords and usernames for everything.  Change these.
* Update the self-signed certificate details

I have tried to harden the mysql and tomcat instances.  This may not be enough for you and no warrenty is expressed or implied. As per the ```LICENCE``` file.

Have fun!

# TODO

mention Ubuntu 1404 ssh mux issue


