<div align="center">

# Huai-Tian

**心清水现月，意定天无云**

独立开发者 · 系统安全与隐私保护

</div>

---

专注三件事：**Android Framework 层的攻与防**、**Windows 内核的硬件虚拟化 Hook**、**后量子端到端加密**。所有项目均由个人兴趣驱动，永久免费、非商业化。

## 技术栈

<img src="https://skillicons.dev/icons?i=kotlin,c,rust,android,windows,linux,git&perline=7" alt="Skills" />

- **Android 逆向 / 框架 Hook** — LSPosed（Xposed API）、Shizuku、system_server 注入、无障碍服务
- **Windows 内核 / 虚拟化** — 内核驱动开发、Intel VT-x（EPT）、AMD SVM（NPT）、Hypervisor
- **密码学 / 安全通信** — Noise 协议、ML-KEM（后量子 KEM）、Argon2、端到端加密设计

## 精选项目

| 项目 | 简介 |
| --- | --- |
| [**ScreenshotFaker**](https://github.com/Huai-Tian/ScreenshotFaker) | Android 截屏隐私保护工具，强反检测：敏感内容防捕获、隐身截屏/录屏/屏幕共享、配置强加密与胁迫自毁（支持 LSPosed / Shizuku / Root） |
| [**ScreenshotDetector**](https://github.com/Huai-Tian/ScreenshotDetector) | 与 ScreenshotFaker 互为攻防对照：从应用层检测截屏、录屏、投屏与录音行为 |
| [**GeptHooks**](https://github.com/Huai-Tian/GeptHooks) | Windows 隐藏 EPT Hook 框架（Intel VT-x）：双 EPT 视图实现零 VM-Exit、零字节修改的内核 Hook，并对自身存在深度隐匿 |
| [**GnptHooks**](https://github.com/Huai-Tian/GnptHooks) | GeptHooks 的 AMD 姊妹篇：基于 SVM 双 NPT 视图，稳态零 VM-Exit |
| [**E2EE-Experiment**](https://github.com/Huai-Tian/E2EE-Experiment) | 单 Rust 二进制、零持久化的端到端加密对话实验：后量子 Noise + ML-KEM，绝不落盘 |
| [**DoNotComplain**](https://github.com/Huai-Tian/DoNotComplain) | LSPosed 模块：让通知被关掉的 App 不再弹「请开启通知」的骚扰，真实开关状态不受影响 |

## GitHub 统计

<img src="https://github-readme-stats.vercel.app/api?username=Huai-Tian&show_icons=true" height="150" alt="GitHub Stats" />
<img src="https://github-readme-stats.vercel.app/api/top-langs/?username=Huai-Tian&layout=compact&langs_count=8" height="150" alt="Top Languages" />
