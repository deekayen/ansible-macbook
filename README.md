deekayen-macbook ansible playbook
=================================

Install Ansible
---------------

According to the [Ansible installation docs](
https://docs.ansible.com/ansible/intro_installation.html#latest-releases-via-pip), the preferred way to install for macOS is via pip:

```
sudo easy_install pip
sudo pip install git+git://github.com/ansible/ansible.git@devel
```

Install Homebrew
----------------

[Some people make a complicated Ansible role for this](https://github.com/geerlingguy/ansible-role-homebrew/network), but I'm only doing it once, so just run the install command from http://brew.sh/ in Terminal!

Clone this Repo
---------------

Yeah, just do that.

Enable SSH
----------

```
sudo systemsetup -f -setremotelogin on
```

Run the playbook
----------------

Ansible makes setup easy.
