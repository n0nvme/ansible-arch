# ansible-arch
ansible playbook for arch linux management

## USAGE:
after reboot to installed system(from non-root user):
```bash
git clone https://github.com/n0nvme/ansible-arch.git
cd ansible-arch
ansible-galaxy install -r requirements.yml
ansible-playbook site.yml
```

## TODO:
- poetry installation
- add user to docker group
- enable daemons
- move username & some other things to variables
- some refactor
- install some hardware specific packages only for one notebook(fingerprint driver for thinkpad for example)
- virtualbox installation
- more fonts
- use reflector config
- create user
- manage user's groups
