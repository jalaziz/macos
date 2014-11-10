osx - OSX Bootstrap Playbook
============================

On a new machine, run:

```bash
easy_install pip
pip install ansible
ansible-pull -K -d /tmp/bootstrap -i /tmp/bootstrap/hosts -U git://github.com/jalaziz/osx.git
```

