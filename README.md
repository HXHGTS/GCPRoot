# GCPRoot
切换root权限并开启密码ssh登录root账户

```
sudo -i
```

```
passwd
```

Debian11:
以用户名admin登录

```
curl https://raw.githubusercontent.com/HXHGTS/AWSECSRoot/master/sshd_config_debian11 > /etc/ssh/sshd_config
/sbin/service sshd restart
```
