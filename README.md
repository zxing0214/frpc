# frpc
## 项目简介
基于 [fatedier/frp](https://github.com/fatedier/frp) 原版 frp 内网穿透客户端 frpc 的一键安装卸载脚本和 docker 镜像.


- GitHub [zxing0214/frpc](https://github.com/zxing0214/frpc)
- Docker [zxing/frpc](https://hub.docker.com/r/zxing/frpc)

## 使用说明
```shell
mkdir frpc;cd frpc
wget https://raw.githubusercontent.com/zxing0214/frpc/master/frpc.ini 
cd ..
docker run zxing/frpc --restart=always --net=host --volume ./frpc:/frpc
# 重启 frpc 容器即可生效
```

## 版本更新
- latest 为最新版
- Tags 为历史版本

## 相关链接
- GitHub [zxing0214/frpc](https://github.com/zxing0214/frpc)
- Docker [zxing/frpc](https://hub.docker.com/r/zxing/frpc)
- 原版frp项目 [fatedier/frp](https://github.com/fatedier/frp)
- 原版frp文档 [gofrp.org](https://gofrp.org/docs)