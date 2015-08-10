# Xroad & vagrant & ansible

Example xroad 6 secure server installation using vagrant + ansible.

## Table of Contents
1. [Quick start](#quick-start)
2. [References](#references)

## Quick start
1. Boot vagrant box
``` Bash
  vagrant up
```

2. Configure vars, look at site.yml

3. Run ansible playbook
``` Bash
  ansible-playbook -vvv ./ansible/site.yml
```

4. On vagrant host, browse to https://localhost:4000

## References
- [KAPA documentation](https://confluence.csc.fi/download/attachments/50177427/Liitynt%C3%A4palvelimen%20asennus%202015_03_23.pdf?version=1&modificationDate=1427125267011&api=v2)
- [Kehitysympäristön päivitys ohjeet](https://confluence.csc.fi/pages/viewpage.action?pageId=51891551)
- [X-road 6.0 security server installation guide](http://x-road.eu/docs/x-road_v6_security_server_installation_guide_1.4.pdf) 
