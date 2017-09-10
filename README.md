# lab_salt_config
configuration files for the master servers

```
Salt Version:
           Salt: 2017.7.1
 
Dependency Versions:
           cffi: 1.10.0
       cherrypy: Not Installed
       dateutil: Not Installed
      docker-py: Not Installed
          gitdb: 0.6.4
      gitpython: 2.1.5
          ioflo: Not Installed
         Jinja2: 2.7.2
        libgit2: 0.26.0
        libnacl: Not Installed
       M2Crypto: Not Installed
           Mako: Not Installed
   msgpack-pure: Not Installed
 msgpack-python: 0.4.8
   mysql-python: Not Installed
      pycparser: 2.18
       pycrypto: 2.6.1
   pycryptodome: Not Installed
         pygit2: 0.26.0
         Python: 2.7.5 (default, Nov  6 2016, 00:28:07)
   python-gnupg: Not Installed
         PyYAML: 3.11
          PyZMQ: 15.3.0
           RAET: Not Installed
          smmap: 2.0.3
        timelib: Not Installed
        Tornado: 4.2.1
            ZMQ: 4.1.4
 
System Versions:
           dist: centos 7.3.1611 Core
         locale: UTF-8
        machine: x86_64
        release: 3.10.0-514.26.2.el7.x86_64
         system: Linux
        version: CentOS Linux 7.3.1611 Core
```

## GITFS
Installing python-pygit2 and libgit2 doesnt cut it. Even if the packages are the newest version. Had to install additionally
GitPython.

