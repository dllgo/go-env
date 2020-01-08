# go-env
Go 一键安装脚本
------
- 支持 **Linux / MacOS / FreeBSD** 等系统
- 支持自定义**版本**
- 支持自定义**GOPATH**

## 安装
### 在线安装
#### 默认安装
```sh
$ curl https://github.com/dllgo/go-env/blob/master/env.sh | bash
```

#### 自定义安装
```sh
$ curl -SL https://github.com/dllgo/go-env/blob/master/env.sh | bash /dev/stdin -v 1.13.5 -d /users/lyg/desktop/go
```

### 离线执行
保存脚本并且命名为 **env.sh**    

```sh
# 默认配置
$ sh env.sh

# 自定义    
$ sh env.sh -v 1.13.5 -d /users/lyg/desktop/go 
```
**使用说明**    
./env.sh -h
