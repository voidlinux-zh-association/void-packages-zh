# void-packages-zh
中文用户可能需要的 VoidLinux 软件包

## 软件包列表

| 软件名                        | 详情                     | 是否开源              |
|------------------------------|-------------------------|----------------------|
| v2rayA                       | v2ray 代理软件            | 开源                 |
| electron-netease-cloud-music | 网易云音乐 electron 客户端 | 客户端开源、服务端闭源  |
| clash                        | 代理软件                  | 开源                 |
| go-musicfox                  | 网易云音乐命令行第三方客户端 | 客户端开源、服务端闭源  |


## 如何使用

请先克隆 `xbps_src`：

```
git clone https://github.com/void-linux/void-packages.git
```

如果网络不好可以使用：

```
git clone https://hub.nuaa.cf/void-linux/void-packages.git
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

# 其他资源
- [voidxanmod Kernel](https://notabug.org/Marcoapc/voidxanmodK)
- [librewolf-voidlinux](https://github.com/index-0/librewolf-voidlinux)
- [hyprland-void](https://github.com/kruceter/hyprland-void)