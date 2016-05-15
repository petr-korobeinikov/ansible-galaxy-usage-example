# ansible-galaxy-usage-example

    $ cp Vagrantfile.dist Vagrantfile
    $ vagrant up
    $ cd ansible
    $ cp ansible.cfg.dist ansible.cfg
    $ ansible-galaxy install -r requirements.yml
    $ ansible-playbook -i inventory/vagrant playbook.yml
