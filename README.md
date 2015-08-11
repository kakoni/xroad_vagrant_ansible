# Xroad & ansible & AWS || Vagrant 

Example xroad 6 secure server installation using vagrant(or ec2) + ansible.

## Table of Contents
1. [Quick start using vagrant](#quick-start)
2. [EC2 Usage](#ec2)
3. [References](#references)

## Quick start
- Boot vagrant box
``` Bash
  vagrant up
```

- Configure vars, look at site.yml

- Run ansible playbook
``` Bash
  ansible-playbook -vvv ./ansible/site.yml
```

- On vagrant host, browse to https://localhost:4000 and complete installation

## EC2
To get started, install EC2.py scripts. See [Amazon Documentation](https://aws.amazon.com/blogs/apn/getting-started-with-ansible-and-dynamic-amazon-ec2-inventory-management/)

- Rename ansible.cfg.ec2 to ansible.cfg and edit accordingly

- Configure vars, look at site.yml (TODO, setup VPC, EIP and Security Groups using ansible)

- Run ansible playbook
``` Bash
  ansible-playbook -vvv ./ansible/site.yml
```

- On ec2 host, browse to https://xxxx:4000 and complete installation


## References
- [KAPA documentation](https://confluence.csc.fi/download/attachments/50177427/Liitynt%C3%A4palvelimen%20asennus%202015_03_23.pdf?version=1&modificationDate=1427125267011&api=v2)
- [Kehitysympäristön päivitys ohjeet](https://confluence.csc.fi/pages/viewpage.action?pageId=51891551)
- [X-road 6.0 security server installation guide](http://x-road.eu/docs/x-road_v6_security_server_installation_guide_1.4.pdf) 
