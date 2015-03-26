osx - OSX Bootstrap Playbook
============================

On a new machine, run:

```bash
wget https://bootstrap.pypa.io/get-pip.py
sudo python get-pip.py
sudo pip install ansible
export PYTHONUNBUFFERED=1
export PYTHONIOENCODING='utf-8'
ansible-pull -K -d /tmp/bootstrap -i localhost, -U https://github.com/jalaziz/osx.git
```

