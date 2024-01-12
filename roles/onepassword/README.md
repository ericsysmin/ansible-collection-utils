# ericsysmin.utils.onepasswordcli

Ansible role to install 1Password CLI.

## Role Variables

None

## Example Playbook

```yaml
- hosts: servers
  tasks:
    - name: Install 1Password CLI
      ansible.builtin.include_role:
        name: ericsysmin.utils.onepasswordcli
```

## License

MIT

## Author Information

Eric Anderson <eric.sysmin@outlook.com>