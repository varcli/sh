# shell脚本

为防止系统没安装curl，使用不了一键命令，使用下面的一键命令之前先执行一次安装curl命令
```sh
apt -y update && apt -y install curl wget sudo || yum install -y curl wget || apk add curl bash
```

- ### (centos、ubuntu、debian、alpine)一键开启SSH
```sh
bash -c  "$(curl -fsSL https://cdn.jsdelivr.net/gh/shidahuilang/pve@main/ssh.sh)"
