# Ansible Role: time
| A role that sets the timezone.

## Installation

Galaxy Link: <https://galaxy.ansible.com/while-true-do/time>

```
ansible-galaxy install while-true-do.time
```

Github Link: <https://github.com/while-true-do/ansible-role-time>

```
git clone https://github.com/while-true-do/ansible-role-time while-true-do.time
```

## Requirements

None.

## Dependencies

None.

## Role Variables

```
# defaults/main.yml
time_timezone: 'Europe/London'
```

## Example Playbook

Simple Example:

```
- hosts: servers
  roles:
    - { role: while-true-do.time }
```

## License

This work is licensed under a [BSD License](https://opensource.org/licenses/BSD-3-Clause).

## Contribute / Bugs

**bug reports:** <https://github.com/while-true-do/ansible-role-time/issues>

**contributers:** <https://github.com/while-true-do/ansible-role-time/graphs/contributors>

## Author Information

**blog:** <https://blog.while-true-do.org>

**github:** <https://github.com/daniel-wtd>

**contact:** [mail@while-true-do.org](mailto:mail@while-true-do.org)
