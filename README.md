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
* `virtualenvs`: Dict of virtual environment to create. With keys:
    * `path`: Virtual environment directory
    * `version`: Virtual environment python version
    * `requirements`: Requirements.txt file to install
* `pythonz_repo`: Git url to the pythonz repository (default to: https://github.com/saghul/pythonz.git)
* `pythonz_version`: Version of pythonz to download (default to: master)


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
  virtualenvs:
    env_1:
      path: /opt/env_1
      version: "3.6.1"
      requirements: requirements.txt
    env_2:
      path: /opt/env_2
      version: "3.6.2"
```

License
-------

MIT

Author Information
------------------

None
