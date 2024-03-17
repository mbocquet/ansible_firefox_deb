# firefox_deb

Ansible role to install Firefox on Debian from official Mozilla repositories.

Tasks are actions taken from there :

https://support.mozilla.org/en-US/kb/install-firefox-linux

Section "install-firefox-deb-package-for-debian-based-distributions".

## Requirements

None.

## Role Variables

See defaults/main.yml for details

## Dependencies

None.

## Install this role as submodule in a git repository

```sh
git submodule add https://git.sekoya.org/mb/ansible_firefox_deb.git roles/firefox_deb
```

## Example Playbook

    - hosts: laptops
      roles:
        - firefox_deb


    - hosts: laptops
      roles:
        - role: firefox_deb
          x: 42

## License

GPLv3

## Author Information

http://www.sekoya.org
