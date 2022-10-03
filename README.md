# GCPRoot
切换root权限并开启密码ssh登录root账户

```
sudo -i
```

```
passwd
```

Debian11:
浏览器登录

```
curl https://raw.githubusercontent.com/HXHGTS/GCPRoot/main/sshd_config_debian11 > /etc/ssh/sshd_config
/sbin/service sshd restart
```
