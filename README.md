pyslackers.python
=========

[![Build Status](https://travis-ci.org/pyslackers/ansible-role-python.svg?branch=master)](https://travis-ci.org/pyslackers/ansible-role-python)

Python3 role for ansible. This supports multiple python versions thanks to pythonz.

Requirements
------------

None

Role Variables
--------------

* `python_versions`: List of valid python 3 versions to install.

Dependencies
------------

None

Example Playbook
----------------

```yml
- role: pyslackers.python
  python_versions:
    - "3.6.2"
    - "3.6.3"
```

License
-------

MIT

Author Information
------------------

None
