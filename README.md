# setup
Mac laptop setup using ansible

1. Install homebrew from: http://brew.sh/

2. Install git via homebrew  
```brew install git```

3. Install ansible via homebrew  
```brew install ansible```

4. Create src/itskarma directory  
```mkdir -p ~/src/itskarma```

5. Clone this repo in ~/src/itskarma and cd into it  
```cd ~/src/itskarma```  
```git clone https://github.com/ItsKarma/setup.git```
```cd ~/src/itskarma/setup```

6. Run ansible-playbook  
```ansible-playbook playbooks/setup.yml```
