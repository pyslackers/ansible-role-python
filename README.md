pyslackers.python
=========

[![Build Status](https://travis-ci.org/pyslackers/ansible-role-python.svg?branch=master)](https://travis-ci.org/pyslackers/ansible-role-python)

Python role for ansible. This supports multiple python versions thanks to pythonz.

Requirements
------------

None

Role Variables
--------------

* `version`: The python version, this must be a valid value in the python ftp site.

Dependencies
------------

None

Example Playbook
----------------

```yml
- role: pyslackers.python
  version: "3.6.2"
```

License
-------

MIT

Author Information
------------------

None
