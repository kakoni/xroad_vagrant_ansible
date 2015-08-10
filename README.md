# Xroad & vagrant & ansible

Example xroad 6 secure server installation using vagrant + ansible.

##Get started

#### 1. Boot vagrant box
``` Bash
  vagrant up
```

#### 2. Configure vars, look at site.yml

#### 3. Run ansible playbook
``` Bash
  ansible-playbook -vvv ./ansible/site.yml
```

#### 4. On vagrant host, browse to https://localhost:4000
