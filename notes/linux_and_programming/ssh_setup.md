---
title: ssh setup
---

## github ssh配置

### 生成key
```
ssh-keygen -t rsa -f ~/.ssh/baidu_id_rsa
```
### 配置～/.ssh/config文件
```
#GitHub
Host github.com
HostName github.com
PreferredAuthentications publickey
IdentityFile ~/.ssh/id_rsa
```
~/.ssh/config 文件权限必须为644

## git 常用命令
git clone --depth 1 --branch v5.0.8 --no-checkout https://github.com/emqx/emqx.git