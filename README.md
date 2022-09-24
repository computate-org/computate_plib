
# Install the plib ansible role

```bash
# Create a directory for the ansible role. 
install -d ~/.ansible/roles/computate.computate_plib

# Clone the plib ansible role. 
git clone git@github.com:computate-org/computate_plib.git ~/.ansible/roles/computate.computate_plib

# Change into the plib ansible role directory. 
cd ~/.ansible/roles/computate.computate_plib
```

# Run the plib ansible playbook to install plib locally. 

```bash
ansible-playbook install.yml
```

Christopher Tate
