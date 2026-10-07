<div align="center">

# Bqops 安装包发布

[![Release](https://img.shields.io/badge/版本-v1.0.0--rc.4-f5a623)](../../releases)
[![平台](https://img.shields.io/badge/平台-Windows%20%7C%20macOS%20%7C%20Linux-8b8b96)](#-下载)
[![试用](https://img.shields.io/badge/试用-7%20天全功能-34d399)](#-试用与授权)
[![License](https://img.shields.io/badge/License-MIT-60a5fa)](./LICENSE)
[![官网](https://img.shields.io/badge/官网-www.bqops.com-f5a623)](https://www.bqops.com/)

**终端 + 网络运维平台** —— 多协议终端 · 跨网段扫描 · 漏洞检测 · 配置备份巡检 · AI Agent

🔒 本地优先：数据全部保存在本机，不上传、不存储用户数据

</div>

---

## 📥 下载 v1.0.0-rc.4

> 主下载源为 **dl.bqops.com**（国内直连快）；GitHub Assets 为同镜像副本。

| 平台 | 文件 | 大小 | 直链 |
|---|---|---|---|
| Windows x64 | `bqops-1.0.0-rc.4-setup-x64.exe` | 330 MB | [主源](https://dl.bqops.com/bqops-1.0.0-rc.4-setup-x64.exe) · [Assets](../../releases/download/v1.0.0-rc.4/bqops-1.0.0-rc.4-setup-x64.exe) |
| macOS Apple Silicon | `bqops-1.0.0-rc.4-macos-arm64.dmg` | 346 MB | [主源](https://dl.bqops.com/bqops-1.0.0-rc.4-macos-arm64.dmg) · [Assets](../../releases/download/v1.0.0-rc.4/bqops-1.0.0-rc.4-macos-arm64.dmg) |
| macOS Intel | `bqops-1.0.0-rc.4-macos-x64.dmg` | 351 MB | [主源](https://dl.bqops.com/bqops-1.0.0-rc.4-macos-x64.dmg) · [Assets](../../releases/download/v1.0.0-rc.4/bqops-1.0.0-rc.4-macos-x64.dmg) |
| Linux deb | `bqops-1.0.0-rc.4-linux-amd64.deb` | 269 MB | [主源](https://dl.bqops.com/bqops-1.0.0-rc.4-linux-amd64.deb) · [Assets](../../releases/download/v1.0.0-rc.4/bqops-1.0.0-rc.4-linux-amd64.deb) |
| Linux AppImage | `bqops-1.0.0-rc.4-linux-x86_64.AppImage` | 331 MB | [主源](https://dl.bqops.com/bqops-1.0.0-rc.4-linux-x86_64.AppImage) · [Assets](../../releases/download/v1.0.0-rc.4/bqops-1.0.0-rc.4-linux-x86_64.AppImage) |

## 🧭 安装说明

**Windows**：双击安装包运行。若 SmartScreen 弹出提示（预发布版本未做代码签名），点击「更多信息 → 仍要运行」。

**macOS**：打开 dmg，将 Bqops 拖入「应用程序」。首次启动若提示无法验证开发者，请**右键点击应用 → 打开**（不要直接双击），或在「系统设置 → 隐私与安全性」中允许。

**Linux**：deb 包用 `sudo dpkg -i <文件>` 或软件中心安装；AppImage 添加执行权限后直接运行（`chmod +x`）。

## ⚖️ 试用与授权

- 下载即享 **7 天全功能体验**（无需注册账号、无需信用卡），到期自动降级为免费版，数据保留
- 免费版核心功能永久可用，连接数不设限；可随时在官网 [申请试用码](https://www.bqops.com/trial.html) 延长体验
- 授权按 **一码一台** 交付，激活码与设备绑定；支持批量离线激活，数据不出内网
- 定价与版本对比见 [官网定价页](https://www.bqops.com/pricing.html)

## 🔄 自动更新

客户端内置更新检查，预发布通道清单：

| 平台 | 清单 |
|---|---|
| Windows | https://dl.bqops.com/rc.yml |
| macOS | https://dl.bqops.com/rc-mac.yml |
| Linux | https://dl.bqops.com/rc-linux.yml |

## 🔏 SHA-512 校验和

<!-- CHECKSUMS:START -->
`bqops-1.0.0-rc.4-setup-x64.exe`  
`g++j3j/PVhIPnmSRqbScIBMxNGqPWPBBcwCrbdoN/k5EZmfDKS8cfU4ROI6Vqm6Rpi4bSRTUwOzTII7rFKnkUA==`
`BqOps-1.0.0-rc.4-mac.zip`  
`RQJJnGxeMbv5/SnPJIwrUe4ICieyCxdsggM3fZoxEEiHantjxi2WOBouOC4MUvmFa3FS2sUcHOIJPGC/gXZ7Mw==`
`BqOps-1.0.0-rc.4-arm64-mac.zip`  
`1DDEY+bonWD+JvFm4g2maYGtjQvVmEdT6iu3kdVVFTEy4t3+sRKLfWLPQGvtre7dIwi5LDC7vhObSrTEWAvBZw==`
`bqops-1.0.0-rc.4-macos-x64.dmg`  
`vaDmk2QOaUcXUw/4q0catnp2vpgWtZKb/XmjYl1LbSVoqyEE6CKex9lC3WSh8UjRP8N+nYUY48JJoI/B5icTVQ==`
`bqops-1.0.0-rc.4-macos-arm64.dmg`  
`J46hm1jQKZ/7m2lhFKQl9fxp+yLDMhsAikgX0YPozJu1f2/J9t+Kv1oKCqX+bL5bDE7iWbo7ewkniJ5/nrygTw==`
`bqops-1.0.0-rc.4-linux-amd64.deb`  
`g63LCAm+eYQ8Esg0zW9OUxNGhD9aINHnuZcy2Ou+A2yU+VktQPM2JYT9eFL2tWfXUZDXfiuEuCuF+glQErhyJg==`
`bqops-1.0.0-rc.4-linux-x86_64.AppImage`  
`wtCJ1222xss2WtCL3x5YWlolrfbK8Wx8AiAQR44VUkcnqjJCXVJX/2NEAUEZbjoq+qW+YwV6nbUUrLN6nfHvbQ==`
<!-- CHECKSUMS:END -->

> ⚠️ 本仓库仅用于发布安装包与更新日志，不含源码。

## 🔗 相关链接

- 官网：https://www.bqops.com/
- 定价：https://www.bqops.com/pricing.html
- 申请试用：https://www.bqops.com/trial.html
- 问题反馈：bqsmartops@163.com
