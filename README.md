<p align=center>
  <br>
  <span>Phicomm K2P Openwrt Autobuild | 斐讯 K2P Openwrt 自动编译（每周一早8点）</span>
  <br>
  <span>Customize your own OpenWrt firmware for Phicomm K2P using Github Actions.</span>
  <br>
  <br>
  <a target="_blank" href="LICENSE" title="License: MIT"><img src="https://img.shields.io/github/license/mashape/apistatus.svg?style=flat-square&label=LICENSE"></a>
  <a target="_blank" href="https://github.com/tjuyy/Phicomm-K2P-Openwrt-Autobuild/stargazers" title="Stars"><img src="https://img.shields.io/github/stars/tjuyy/Phicomm-K2P-Openwrt-Autobuild.svg?style=flat-square&label=Stars"></a>
  <a target="_blank" href="https://github.com/tjuyy/Phicomm-K2P-Openwrt-Autobuild/fork" title="Forks"><img src="https://img.shields.io/github/forks/tjuyy/Phicomm-K2P-Openwrt-Autobuild.svg?style=flat-square&label=Forks"></a>
  <br>
  <a target="_blank" href="https://github.com/tjuyy/Phicomm-K2P-Openwrt-Autobuild/actions" title="GitHub Actions Workflow Status"><img alt="GitHub Workflow Status" src="https://img.shields.io/github/workflow/status/tjuyy/Phicomm-K2P-Openwrt-Autobuild/Build%20OpenWrt%20for%20K2P?style=for-the-badge"></a>
</p>

<p align="center">
  <a href="#usage">Usage</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#info">Info</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#features">Features</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#acknowledgments">Acknowledgments</a>
  &nbsp;&nbsp;&nbsp;|&nbsp;&nbsp;&nbsp;
  <a href="#license">License</a>
</p>


## Usage

1. Star and Fork [this repository](https://github.com/tjuyy/Phicomm-K2P-Openwrt-Autobuild)
2. Click the `Action` button of your own forked repository
3. Click the `Build Lean's OpenWrt for K2P` under all workflows
4. Click the `Run workflow` button on the right, you can input some logs here (optional)
5. Github Actions workflow will be triggered and run automaticlly
6. Wait completion of the workflow and download files from `Aritifact`

## 使用方法（简体中文）

1. Star and Fork [this repository](https://github.com/tjuyy/Phicomm-K2P-Openwrt-Autobuild)
2. 在你的forked repo中，点击上方的 `Action` 按钮 
3. 点击左侧的all workflows下方的 `Build Lean's OpenWrt for K2P`
4. 点击右侧的 `Run workflow` 按钮，这里可以输入一些日志 (可选的)
5. Github Actions workflow 会被触发并自动运行编译
6. 等待workflow工作完成，从 `Aritifact`中下载生成的文件

## Info

- gateway: 192.168.1.1

## Features

### Network
- IPv6
- NAT6
- Shadowsocks
- V2Ray
- Trojan

### Tools
- htop
- curl
- wget
- iperf3
- tcpdump
- luci-app-commands
- luci-app-ttyd
- luci-app-webadmin
- luci-app-wrtbwmon

## Acknowledgments

- [GitHub Actions](https://github.com/features/actions)
- [tmate](https://github.com/tmate-io/tmate)
- [OpenWrt](https://github.com/openwrt/openwrt)
- [Lean's OpenWrt](https://github.com/coolsnowwolf/lede)
- [P3TERX/Actions-OpenWrt](https://github.com/P3TERX/Actions-OpenWrt)
- [P3TERX/debugger-action](https://github.com/P3TERX/debugger-action)
- [skytotwo/NanoPi-R1S-Build-By-Actions](https://github.com/skytotwo/NanoPi-R1S-Build-By-Actions)

## License

MIT © [tjuyy](https://github.com/tjuyy)

