---
tag: 'markdown'
date: '2024/7/20'
---

# Lutris 安装问题

如果电脑配置了代理，Lutris 可能会卡在安装 DXVK 等 Runtime 库

可以在终端这样打开

```bash
all_proxy="http://xxx.xxx.xx.xx:xxxx" lutris
```

推荐在 flathub 安装 Lutris，打开命令要变成 `flatpak run net.lutris.Lutris`