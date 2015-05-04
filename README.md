# [Ansible: Reliably Deploying Rails](https://github.com/jluckyiv/ansible-reliably-deploying-rails)

This is an [Ansible](http://www.ansible.com/home) implementation of the setup in the book [Reliably Deploying Rails](https://leanpub.com/deploying_rails_applications), which uses [Chef](https://www.chef.io/chef/). 

### Dependencies
- [Ansible](http://www.ansible.com/home)

You'll also need to install the following [Ansible Galaxy](https://galaxy.ansible.com/) roles, with the `ansible-galaxy install` command, e.g.,
```
ansible-galaxy install geerlingguy.memcached
```

- [geerlingguy.memcached](https://galaxy.ansible.com/list#/roles/1938)
- [geerlingguy.redis](https://galaxy.ansible.com/list#/roles/468)
- [geerlingguy.ruby](https://galaxy.ansible.com/list#/roles/470)
- [jdauphant.nginx](https://galaxy.ansible.com/list#/roles/466)
- [patrik.uytterhoeven.PostgreSQL-For-RHEL6x](https://galaxy.ansible.com/list#/roles/738)
- [Stouts.nodejs](https://galaxy.ansible.com/list#/roles/983)

