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

## 补救措施

如果在网络受阻的情况下打开 Lutris，且左下角的安装卡住

这时候如果重新打开 Lutris 会发现没有重新发起 DXVK 等库的安装

1. 可以点击右上角的菜单，打开 Lutris 设置
2. 选择 Updates
3. 找到下面的 Runtime Updates 点击重新安装