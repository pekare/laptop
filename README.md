# laptop

# install ansible
```
sudo apt install ansible -y
```

# clone 
```
mkdir ~/github
cd ~/github
git clone https://github.com/pekare/laptop.git
```

# run playbook
```
cd ~/github/laptop
ansible-playbook -K site.yml
```
