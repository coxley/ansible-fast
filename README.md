# ansible-fast

Performance tweaks for Ansible-managed hosts.

Description
-----------

* Disables DNS lookups for SSH and sudo.
* Adds the system's hostname to `/etc/hosts`.
* Adjusts sudoers config to work with ssh-agent.

Tunables
--------
* None

Dependencies
------------
* None

License
-------
[MIT](https://tldrlegal.com/license/mit-license)

Contributors
------------
* [Chris Olstrom](https://colstrom.github.io/) | [e-mail](mailto:chris@olstrom.com) | [Twitter](https://twitter.com/ChrisOlstrom)
