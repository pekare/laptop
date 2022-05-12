# laptop

# install ansible
sudo apt install ansible -y

# clone 
mkdir ~/github
cd ~/github
git clone git@github.com:pekare/laptop.git

# run playbook
ansible-playbook -K site.yml
