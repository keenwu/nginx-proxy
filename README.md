Ansible / nginx-proxy
======================

Ansible playbook to setup an Nginx proxy and virtual host for your web app.



Usage
-----

Create an inventory file with the servers that you want to Node.js on or use `$ANSIBLE_HOSTS`.

if connecting with root:

    ansible-playbook -i inventory-file -u root main.yml

if sudoing:

    ansible-playbook -i inventory-file -K main.yml



Ansible
-------

Not sure what Ansible is? Read the getting started here: http://procbits.com/2013/09/08/getting-started-with-ansible-digital-ocean


Nginx
-----

Read docs here: http://nginx.org/en/docs/



Todo
----

- make OS agnostic
- support serving of static files through Nginx


License
-------

MIT/X11, Copyright 2013, JP Richardson

