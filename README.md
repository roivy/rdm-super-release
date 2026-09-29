# RDM Super

多线程下载管理器，Windows 桌面端。由 Roivy Mao 开发。

## 功能

- **HTTP 分段并行下载**：文件切块 + 工作池调度；断点续传（块位图）；服务器文件变更
  自动检测（If-Range 锚点，杜绝续传拼接出损坏文件）；被限流自动冷却退避、恢复后自动提速
- **平台视频**（B站 / YouTube / 抖音 等 1800+ 站点）：清晰度选择，最高 4K；
  音视频自动合并；默认最高画质（VP9），同分辨率可选 H.264/MP4；
  任意视频可一键「转换为通用 MP4」
- **流媒体**：HLS (m3u8) 码率选择 / AES-128 解密 / 直播追更
- **FTP / SFTP / BT 磁力 / 整站抓取**（Site Grabber：同主机递归、深度可控）
- **完成自动化**：压缩包自动解压（zip/7z）、全部完成后关机/退出/执行脚本、Webhook 通知、定时下载
- **浏览器插件**（Chrome/Edge）：网页媒体一键接管下载
- **站点加速**：HuggingFace 令牌与镜像、GitHub Release 镜像加速
- **代理**：HTTP / SOCKS5 / SOCKS4
- 分类保存目录、开机自启动进托盘、外部 HTTP API 与 AI 助手（MCP）接入

## 安装

1. 从 [Releases](https://github.com/roivy/rdm-super-release/releases) 下载最新的
   `RDM-Super-Setup-x.y.z.exe`
2. 双击安装（按用户安装，无需管理员权限；升级直接覆盖安装，任务与设置完整保留）
3. 开始菜单启动「RDM Super」

浏览器插件：下载 `RDM-Super-BrowserExtension-x.y.z.zip` 解压到固定目录，
`chrome://extensions` 打开开发者模式 → 加载已解压的扩展程序。

## 使用指引

- **日常下载**：点「添加 URL」粘贴链接（支持直链 / m3u8 / 磁力 / 种子 / 平台视频页链接），
  或用浏览器插件在网页里一键接管
- **进度查看**：主列表实时显示进度/速度/剩余时间；双击任务打开文件，右键更多操作；
  按住左键拖动可框选多个任务
- **设置中心**：每项配置都标了「什么时候需要动它」，一般保持默认即可
- **软件更新**：设置 → 检查更新（自动从本仓库 Releases 拉取并静默升级）

## 支持

问题反馈请到本仓库 Issues。

---

Copyright © 2026 Roivy Mao. All Rights Reserved.
