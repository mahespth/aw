# aw
Ansible Wrapper, execute ansible playbooks like native *nix commands.


# Idea
To be able to execute playbooks on the system by calling them by an executeable name without having to worry about where they are located and the inventories, vars, ansible settings etc. These will all be provided by configuration files either held locally or in from git repo (cached?).

To use it you will link (sym) the name of your playbook to aw and from that it will determine the location of the playbook and its requirements and execute as appropriate.

# Python..
It will be in python3 with 2 compatibility due to the number of legacy systems that I personally need it to execute on.

# Config Layout

note sure yet needs more thought but will attempt to align it with *Ansible* flow.

