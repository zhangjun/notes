# publish gitbook use travis ci

# setup environment
```
dnf module install nodejs:12
npm install gitbook-cli -g
npm config set registry https://registry.npm.taobao.org
```
# setup gitbook
```
gitbook install 
gitbook init
gitbook build
gitbook serve
```

# ref
[gitbook-template](https://github.com/riskers/gitbook-template)
