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
- fix poetry && bumpversion installation
- add user to docker group
- enable daemons
- move username & some other things to variables
- fix oh-my-fish installation
- set fish theme
- some refactor
- auto install roles from ansible-galaxy
- even-better-ls installation
- fix alias for even-better-ls
- install some hardware specific packages only for one notebook(fingerprint driver for thinkpad for example)
- virtualbox installation
- more fonts

## EPIC TODO:
 - add reflector(as daemon)
 - create non-root sudo user