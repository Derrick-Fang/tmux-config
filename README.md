# tmux 配置

个人 tmux 配置仓库。

## 文件说明

- `tmux.conf` — 当前使用的主配置，软链接到 `~/.tmux.conf`
  - Prefix 改为 `Ctrl + a`
  - 鼠标支持、Vim 风格窗格切换
  - Powerline 箭头风格状态栏（Midnight Blue 配色）
- `archive/` — 历史配置备份（Oh my tmux local 配置、旧备份）

## 安装

```bash
ln -sf ~/tmux-config/tmux.conf ~/.tmux.conf
tmux source-file ~/.tmux.conf   # 或重启 tmux
```
