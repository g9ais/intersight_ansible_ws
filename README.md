Code for Intersight and Ansible Workshop
Inspired by https://github.com/ucs-compute-solutions/FlashStack_IMM_Ansible

Make sure to get intersight Ansible Collection installed on your system

## Requirements

- Ansible v2.15.0 or newer
- Python 3.7 or newer (Older Python versions are no longer supported with this collection)


## Installation

Ansible must be installed
```
sudo pip install ansible
```

Before using this collection, you need to install it with the Ansible Galaxy command-line tool:
```
ansible-galaxy collection install cisco.intersight
```
Check its version:
```
ansible-galaxy collection list cisco.intersight
```
Update it if not latest:
```
ansible-galaxy collection install cisco.intersight --upgrade
```


You can also include it in a requirements.yml file and install it with ansible-galaxy collection install -r requirements.yml, using the format:

```yaml
collections:
  - name: cisco.intersight
```