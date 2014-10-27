sensu-playbook
==============

sensu-playbook for Ansible on Centos 6.5

This will automate the documentation process for a single node.
Uchiwa GUI will be installed

Before running the playbook make sure to have direct access to the machine
Make sure you have the server certificate in your ~/.ssh/id_rsa

<syntaxhighlight lang="bash">
[prompt] # exec ssh-agent bash <br>
[prompt] # ssh-add <br>
Enter passphrase for /root/.ssh/id_rsa: <br>
Identity added: /root/.ssh/id_rsa (/root/.ssh/id_rsa) <br>
</syntaxhighlight>
