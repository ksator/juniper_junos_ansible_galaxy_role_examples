Playbooks to execute JSNAPy tests on Junos devices
```
$ ansible --version
$ ansible-galaxy Juniper.junos list
$ pip list | grep 'eznc\|jsnapy\|jxmlease'
```
```
$ more /etc/jsnapy/jsnapy.cfg
```
```
$ ansible-playbook audit/jsnapy_snapcheck.yml
$ ls audit/rendered_template/
$ ls ~/jsnapy/snapshots
```
```
$ ansible-playbook audit/jsnapy_snap_snap_check.yml
$ ls audit/rendered_template/
$ ls ~/jsnapy/snapshots
```

