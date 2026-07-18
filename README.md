# 言序安装入口

此仓库通过 GitHub Pages 发布言序与言包的短安装地址：

- `https://get.yanxu.dev`：言序 macOS / Linux 安装器
- `https://get.yanxu.dev/windows`：言序 Windows PowerShell 安装器
- `https://get.yanxu.dev/yanbao`：言包 macOS / Linux 安装器
- `https://get.yanxu.dev/yanbao/windows`：言包 Windows PowerShell 安装器
- `https://get.yanxu.dev/packages/v1/yanxu-gui/index.json`：言窗 1.0 只读包索引

Pages 工作流在发布时从两个官方仓库的 `main` 分支获取脚本，并每天刷新一次，避免短链接中的脚本副本过期。只读包索引固定到正式 Release 的注册表专用六目标归档及其 SHA-256；部署前会重新下载制品并核对摘要。
