# 🎮 Quartero's Curios · EXP Tracker / 奇货郎任务经验追踪器

[中文](#中文) · [English](#english)

---
为了肝奇货郎任务自己用的小工具，以下内容全部由kimi生成。



## 中文

一个为 DOTA2 活动设计的移动端经验追踪工具。单文件、零依赖、纯前端，数据只存在你自己的设备上。

### ✨ 功能

- ⏰ **活动倒计时**：实时显示剩余时间，自动计算剩余天数与日均需获取经验
- 📈 **升级进度**：从零追踪经验，满 1000 自动升级，当前等级实时变化
- ⚖️ **模式效率分析**：以基础胜率为先验，随对局记录自动修正胜率，分别计算普通 / 加速模式的场均经验与每分钟经验，直接告诉你刷哪个模式更划算
- 📅 **比赛日历**：月视图热力图，一眼看出每天打了几场
- 📊 **每日统计**：近 14 天经验汇总条形图，达标日金色高亮
- 🌍 **多语言**：中文 / English / Русский，按手机系统语言自动切换
- 📤 **数据备份**：一键导出 / 导入 JSON 备份，换机无忧
- 📱 **iOS App 体验**：Safari「添加到主屏幕」后全屏运行，Quartero 主题图标

### 🚀 使用方法

1. 用 Safari 打开部署后的网址；
2. 点分享按钮 →「添加到主屏幕」；
3. 桌面出现 Quartero 图标，点开即可全屏使用。

> ⚠️ 请固定从主屏幕图标进入。iOS 的主屏幕 Web App 与 Safari 浏览器是两套独立存储，混用会导致记录对不上。

### 🛠️ 自己部署（Fork 或下载）

1. Fork 本仓库，或下载 `index.html` 与 `apple-touch-icon.png`；
2. 仓库 **Settings → Pages → Deploy from a branch → main / (root)**；
3. 访问 `https://<你的用户名>.github.io/<仓库名>/`。

### 🔒 隐私

所有数据通过 `localStorage` 存储在你设备的浏览器中，不经过任何服务器，作者与其他用户都无法看到你的记录。清除浏览器网站数据会删除记录，请定期使用导出功能备份。

### 📝 技术栈

HTML5 + CSS3 + Vanilla JavaScript，无框架、无依赖、无构建步骤。

---

## English

A mobile-first EXP tracker for DOTA2 events. Single file, zero dependencies, pure front-end — your data never leaves your device.

### ✨ Features

- ⏰ **Event Countdown**: live countdown with days left and daily EXP target
- 📈 **Level Progress**: track EXP from zero, auto level-up every 1000 EXP
- ⚖️ **Mode Efficiency Analysis**: Bayesian-adjusted win rate (base rate + your records), per-game and per-minute EXP for Normal vs Turbo — know which mode farms faster
- 📅 **Match Calendar**: monthly heatmap showing games played per day
- 📊 **Daily Stats**: 14-day bar chart, gold highlight when daily target is met
- 🌍 **i18n**: 中文 / English / Русский, auto-detected from system language
- 📤 **Backup**: one-tap JSON export / import
- 📱 **iOS App Mode**: full-screen via "Add to Home Screen", Quartero-themed icon

### 🚀 Getting Started

1. Open the deployed URL in Safari;
2. Tap Share → "Add to Home Screen";
3. Launch from the Quartero icon for a full-screen app experience.

> ⚠️ Always launch from the Home Screen icon. iOS keeps separate storage for Home Screen web apps and Safari tabs — mixing them will split your records.

### 🛠️ Deploy Your Own

1. Fork this repo, or download `index.html` and `apple-touch-icon.png`;
2. **Settings → Pages → Deploy from a branch → main / (root)**;
3. Visit `https://<your-username>.github.io/<repo-name>/`.

### 🔒 Privacy

All data lives in your device's browser via `localStorage`. Nothing is sent to any server. Clearing browser site data will erase your records — export backups regularly.

### 📝 Tech Stack

HTML5 + CSS3 + Vanilla JavaScript. No frameworks, no dependencies, no build step.

---

## Version / 版本

See `VERSION` constant in `index.html` and the version history in the project doc.
当前版本见 `index.html` 中的 `VERSION` 常量。
