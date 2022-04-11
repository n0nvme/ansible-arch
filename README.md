# ansible-arch
ansible playbook for arch linux management

## USAGE:
after reboot to installed system(from non-root user):
```bash
git clone https://github.com/n0nvme/ansible-arch.git
cd ansible-arch
ansible-galaxy install -r requirements.yml
ansible-playbook site.yml -K
```