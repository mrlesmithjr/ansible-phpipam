# ansible-phpipam

An [Ansible](https://www.ansible.com) role that installs/configures [phpIPAM](http://phpipam.net/)

- Options are in place for HA DB setup if desired.

## Requirements

Install required Ansible role dependencies...

```bash
sudo ansible-galaxy install -r requirements.yml
```

## Usage

Logging into phpIPAM...
http://iporhostname/phpipam/?page=login

Default phpIPAM login is

```bash
admin/ipamadmin
```

## Role Variables

[defaults/main.yml](defaults/main.yml)

## Dependencies

Reference [requirements](#requirements)

## Example Playbook

```yaml
- hosts: all
  become: true
  vars:
  roles:
    - role: ansible-apache2
    - role: ansible-mariadb-mysql
    - role: ansible-phpipam
```

## License

BSD

## Author Information

Larry Smith Jr.

- [@mrlesmithjr](https://www.twitter.com/mrlesmithjr)
- [EverythingShouldBeVirtual](http://everythingshouldbevirtual.com)
- [mrlesmithjr@gmail.com](mailto:mrlesmithjr@gmail.com)
