## Setup

    ## install ansible
    Install Xcode (should already be installed if you are running chef)
    sudo easy_install pip
    sudo pip install ansible --quiet

## Usage

### Edit the config files

    # Edit ~/roles/switches/var/main.yml

    Add a new line using the first line as an example

### Running Ansible

    # Runing Ansible
    
    ansible-playbook -i ansible-hosts site.yml 
