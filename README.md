# void-packages-zh
中文用户可能需要的 VoidLinux 软件包

## 软件包列表

| 软件名                        | 详情                          | 是否开源              |
|------------------------------|------------------------------|----------------------|
| v2rayA                       | v2ray 代理软件                | 开源                 |
| electron-netease-cloud-music | 网易云音乐 electron 客户端      | 客户端开源、服务端闭源  |
| clash                        | 代理软件                      | 开源                 |
| go-musicfox                  | 网易云音乐命令行第三方客户端      | 客户端开源、服务端闭源  |
| clash-geoip                  | 部分代理软件依赖的 GeoLite2 数据 | ？                   |
| clash-meta                   | 代理软件                       | 开源                 |

## 如何使用

在此之前请安装 `xtools` 以方便以后的操作：

```
# xbps-install -S xtools
```

请先克隆 `xbps_src`：

```
$ git clone https://github.com/void-linux/void-packages.git --depth 1
```

如果网络不好可以使用：

```
$ git clone https://hub.nuaa.cf/void-linux/void-packages.git
```

再克隆此仓库：

```
$ git clone https://github.com/voidlinux-zh-association/void-packages-zh
```

然后选择软件包进行编译：

```
$ cp -a void-packages-zh/srcpkg/软件包名 void-packages/srcpkgs/
$ cd void-packages
$ ./xbps-src binary-bootstrap
$ ./xbps_src pkg 软件包名
```

编译完了，就可以安装了：

```
$ xi 软件包名 #确保是在 void-packages 目录中
```

# 其他资源
- [voidxanmod Kernel](https://notabug.org/Marcoapc/voidxanmodK)
- [librewolf-voidlinux](https://github.com/index-0/librewolf-voidlinux)
- [hyprland-void](https://github.com/Fadest/hyprland-void)
- [cde-for-linux-void](https://github.com/johna23-lab/cde-for-linux-void)
