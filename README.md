[![Build Status](https://travis-ci.org/while-true-do/ansible-role-time.svg?branch=master)](https://travis-ci.org/while-true-do/ansible-role-time)

# Ansible Role: Time
| A role that sets the timezone.

## Motivation
Setting the correct timezone is needed on every computer system.

## Installation
Install from [Ansible Galaxy](https://galaxy.ansible.com/while_true_do.time)

```
ansible-galaxy install while_true_do.time
```

Install from [Github](https://github.com/while-true-do/ansible-role-time)

```
git clone https://github.com/while-true-do/ansible-role-time.git while_true_do.time
```

## Requirements

**Used Modules**

-   [timezone_module](http://docs.ansible.com/ansible/latest/timezone_module.html)

## Role Variables
```yaml
# defaults/main.yml
wtd_time_timezone: "Europe/London"

wtd_time_daemon: "chrony"
```

## Dependencies

-   [ansible-role-chrony](https://github.com/while-true-do/ansible-role-chrony)

## Example Playbook
Simple Example:

```yaml
- hosts: servers 
  roles:
    - { role: while_true_do.time }
```

Advanced Example:

```yaml
- hosts: servers 
  roles:
    - { role: while_true_do.time, wtd_time_timezone: "Europe/Berlin" }
```

## Contribute / Bugs

Thank you so much for considering to contribute. Every contribution helps us.
We are really happy, when somebody is joining the hard work. Please have a look 
at the links first.

-   [Contribution Guidelines](./docs/CONTRIBUTING.md)
-   [Create an issue or Request](https://github.com/while-true-do/ansible-role-time/issues)
-   [See who was contributing already](https://github.com/while-true-do/ansible-role-time/graphs/contributors)

## License
This work is licensed under a [BSD License](https://opensource.org/licenses/BSD-3-Clause).

## Author Information

Blog: [blog.while-true-do.org](https://blog.while-true-do.org)

Mail: [hello@while-true-do.org](mailto:hello@while-true-do.org)
