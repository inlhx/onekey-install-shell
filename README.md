frp服务端一键安装脚本
===========
安装命令
 

### Install

```Bash
wget --no-check-certificate https://raw.githubusercontent.com/inlhx/onekey-install-shell/master/frps/install-frps.sh -O ./install-frps.sh
chmod 700 ./install-frps.sh
./install-frps.sh install
```

### UnInstall
```Bash
    ./install-frps.sh uninstall
```
### Update
```Bash
    ./install-frps.sh update
```
### 服务器管理
```Bash
    Usage: /etc/init.d/frps {start|stop|restart|status|config|version}
```

附带上客户端:
