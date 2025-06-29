# Xposed Freely 模块增强功能集

本模块是一个基于 Xposed 的增强工具，兼容主流社交与短视频应用（如微信、抖音、Soul 等），专为提升使用体验与功能自由度而设计。


[![GitHub stars](https://img.shields.io/github/stars/Xposed-Modules-Repo/me.build?label=stars)](https://github.com/Xposed-Modules-Repo/me.build/stargazers)
[![GitHub Downloads](https://img.shields.io/github/downloads/Xposed-Modules-Repo/me.build/total?label=Downloads)](https://github.com/Xposed-Modules-Repo/me.build/releases)
[![GitHub Latest Release](https://img.shields.io/github/v/release/Xposed-Modules-Repo/me.build)](https://github.com/Xposed-Modules-Repo/me.build/releases/latest)

[![Telegram Group](https://img.shields.io/badge/Freely用户交流群-群组-blue.svg?logo=qq)](https://qm.qq.com/cgi-bin/qm/qr?k=jPy6zzSs5sjv_jPAhD2s9NJuKNQdQT2p&jump_from=webapi&authKey=vfpbIAz3YtgFqv4I1I7pYrkK9XmUBr5UmQoBIXdcH3Nfm8Au8IorwUZo2EkN+3Fq) [![Telegram Group](https://img.shields.io/badge/Freely会员交流群-群组-blue.svg?logo=qq)](https://qm.qq.com/cgi-bin/qm/qr?k=K4Ps-ehEFrD5D-zEP-E-_5aAg4LSFyjq&jump_from=webapi&authKey=T5UKO1ceTdpF6T79TbI+7T45sZx18t5wxKaacW0iE5xgfHSO2D9XZpc3Np5FTvDy)


Freely下载地址:https://pay.nnnen.com/Index/DownFreely


---


## ✅ 支持框架  [LSPosed](https://github.com/LSPosed/LSPosed) | [LSPatch](https://github.com/LSPosed/LSPatch)



## 支持应用

* 微信（WeChat）
* 抖音（Douyin）
* Soul
* 快手 / 快手极速版
* 小红书
* 番茄免费小说 / 番茄畅听
* 百度贴吧
* 七猫免费小说
* 皮皮搞笑
* 以及更多正在适配的 App 和功能（持续更新中）
---


## ✨ 功能总览(理论支持所有最新版本)

### 📱 微信（WeChat）增强功能

* **消息增强**：

  * 消息防撤回 / 自定义防撤回提示
  * 消息时间格式美化、自定义显示、自定义样式
  * 消息复读、自动查看原图
* **界面美化**：

  * 自定义时间文字颜色/大小/圆角、全局聊天气泡样式设置
* **朋友圈增强**：

  * 去除广告、隐藏“部分朋友可见”按钮、发圈功能支持
* **语音视频控制**：

  * 拦截好友语音/视频通话
  * 通话时不打断音乐、支持看视频
* **自动化便捷操作**：

  * 自动登录确认、自动勾选原图
  * 长按快速设置备注、资料、清除未读
* **辅助功能**：

  * 虚拟微信运动步数、余额伪造、隐藏微信号、全局透明头像

### 📹 抖音（Douyin）增强功能

* **内容与广告清理**：

  * 去除启动/闪屏/广告视频、小游戏、推荐卡片等
* **自动操作**：

  * 自动滑动、点赞、评论（支持关键词、黑白名单、延迟等）
  * 评论小尾巴设置、自动关注、自动倍速播放
* **内容下载与控制**：

  * 无水印视频/图集下载、评论长按菜单增强
  * 隐藏页面按钮（如作者头像、进度条、Tab等）

### 💬 Soul 增强功能

* **聊天增强**：

  * 消息防撤回、聊天记录修改、语音/图片下载
  * 自动点赞、关注、评论、自动回复（支持延迟和筛选）
* **资料与互动**：

  * 浏览器打开头像/背景图、复制用户信息
  * 增加访客/播放次数、主页自动点赞/下载
* **解除限制与增强**：

  * 解锁 VIP、隐藏关注、移除聊天限制、禁用青少年模式

### 🎥 快手 / 快手极速版

* **广告与限制解除**：

  * 去除广告、青少年弹窗、直播、下载限制等
* **内容下载**：

  * 主页自动下载图片和视频、无水印下载

### 📷 小红书

* 无水印图片和视频下载

### 📚 番茄小说 / 番茄畅听 / 七猫小说

* 解锁本地 VIP、去除广告与弹窗限制

### 🧵 百度贴吧

* 自动签到、清爽界面、屏蔽更新弹窗

### 🐸 皮皮搞笑

* 去除广告与青少年弹窗、无水印内容下载

---

## ⚙️ 使用说明

1. 安装 [LSPosed](https://github.com/LSPosed/LSPosed) 框架
2. 安装本模块并在 LSPosed 中启用
3. 重启目标 App 查看效果
4. 可通过模块配置界面开启/关闭各项功能

---

## 📌 注意事项

* 所有功能皆可自由开关配置
* 部分功能支持关键词、时间、注册天数等筛选逻辑
* 本模块不会上传或收集任何用户数据
* 请关闭框架的Xposed API 调用保护

---

## 📄 开源与贡献

欢迎提交 [Issues](https://github.com/Xposed-Modules-Repo/me.plusne/issues) 与 [PRs](https://github.com/Xposed-Modules-Repo/me.plusne/pulls)！如果你希望适配更多应用或扩展功能，欢迎共建。

---

## 🛡️ 免责声明

本模块仅供学习与技术研究使用，请勿用于任何违反法律法规的用途。作者不对使用本模块造成的任何后果承担责任。

---

❤️ 如果你喜欢这个模块，欢迎 Star、分享或提出建议！
