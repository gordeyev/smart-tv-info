# Tizen, Orsay, webOS, NetCast

```shell
sdb -s
```

WGT_FILE_PUSH_COMMAND
```shell
sdb -s 172.31.137.22:26101 push tizen/build/Wits.wgt /home/owner/share/tmp/sdk_tools/
```

APP_INSTALL_COMMAND
```shell
sdb -s 172.31.137.22:26101 shell 0 vd_appinstall Wits /home/owner/share/tmp/sdk_tools/Wits.wgt
```

APP_UNINSTALL_COMMAND
```shell
sdb -s 172.31.137.22:26101 shell 0 vd_appuninstall UQFmc9jZyO
```

APP_LAUNCH_COMMAND
```shell
sdb -s 172.31.137.22:26101 shell 0 was_execute UQFmc9jZyO.Wits
```

APP_LAUNCH_DEBUG_MODE_COMMAND
```shell
sdb -s 172.31.137.22:26101 shell 0 debug UQFmc9jZyO.Wits
```

get id: base.xml
<tizen:application id="UQFmc9jZyO.Wits" package="UQFmc9jZyO" required_version="2.3"/>

```shell
tizen security-profiles list
```

```shell
tizen security-profiles set-active -n <profile name>
```
