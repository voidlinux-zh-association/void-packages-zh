# void-packages-zh
中文用户可能需要的 VoidLinux 软件包

## 软件包列表

|          软件名               |             详情         |       是否开源        |
|------------------------------|-------------------------|----------------------|
|          v2rayA              |    v2ray 代理软件        |          开源         |
| electron-netease-cloud-music | 网易云音乐 electron 客户端 | 客户端开源、服务端不开源 |

## 如何使用

请先克隆 `xbps_src`：

```
git clone https://github.com/void-linux/void-packages.git
```

再克隆此仓库：

```
git clone https://github.com/voidlinux-zh-association/void-packages-zh
```

然后选择软件包进行编译：

```
cp -a void-packages-zh/srcpkg/软件包名 void-packages/srcpkgs/
./xbps_src pkg 软件包名
```
