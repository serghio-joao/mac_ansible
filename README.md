# setup
Mac laptop setup using ansible

1. Install homebrew from: http://brew.sh/

2. Install git via homebrew  
```brew install git```

3. Install ansible via homebrew  
```brew install ansible```

4. Create src/mac_ansible directory  
```mkdir -p ~/src/mac_ansible```

5. Clone this repo in ~/src/mac_ansible and cd into it  
```cd ~/src/mac_ansible```  
```git clone https://github.com/serghio-joao/mac_ansible.git```
```cd ~/src/mac_ansible/setup```

6. Run ansible-playbook  
```ansible-playbook playbooks/setup.yml```
