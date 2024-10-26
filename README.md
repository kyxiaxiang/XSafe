# XSafe

> **XSafe** is a lightweight defense tool I created casually. It's designed to detect "Silver Foxes" (a term used here to refer generally to Winos) and some C2/RAT samples. 

XSafe focuses on enhancing dynamic detection and alerting capabilities, without static protection, making it more of an auxiliary tool rather than a full-fledged security solution. It has been tested against multiple "Silver Fox" family samples, successfully intercepting all of them. The tool supports both x64 and x86 architectures.

**XSafe 是一个轻量级的防护小工具，由我随手制作。主要用于检测 “银狐”（泛指 Winos）和部分 C2/RAT 样本。**

XSafe 专注于动态检测和告警功能，并不具备静态防护能力，因此更适合作为辅助程序使用，而非全面的安全解决方案。已测试多个“银狐”家族样本，均成功狙杀。工具支持 x64 和 x86 架构。

---

## Features / 特点

- **Dynamic Detection & Alerts / 动态检测与告警**：XSafe 提供轻度的防护功能，能够实时检测并发出告警，但没有静态防护能力。
- **Easy to Use / 使用简单**：无需驱动签名，基于 DLL 注入（R3）实现保护，支持 x64 和 x86 架构。
- **Compatibility / 兼容性**：适合蓝队人员或安全爱好者，在受控环境中用作辅助工具。

---

## Installation & Usage / 安装与使用

1. **Download & Run**: After downloading, run `XSafeClient.exe` **as Administrator**. The program will automatically copy the required DLL file to `C:\` (quick and straightforward setup).
2. **Background Monitoring**: XSafe runs in the background, monitoring and injecting into all injectable processes for effective detection.
3. **Safe & Offline**: XSafe operates without any external connections, so it’s safe to use without concerns about unwanted data transmission.

**下载后运行 `XSafeClient.exe`（需管理员权限），程序会自动将 DLL 文件复制到 `C:\`。后台自动监控，注入所有可以注入的进程，确保提供实时检测。本程序绝无外联行为，放心使用。**

---

## Usage Suggestions / 使用建议

1. **Virtual Machine Testing / 虚拟机测试**：由于不开源，推荐在虚拟机中进行测试。
2. **Whitelist Addition / 添加白名单**：为提高安全性，可将 XSafe 添加至安全软件的白名单中。
3. **Low False Positive Rate / 低误报率**：误报几率较低，可作为可靠的二级防护工具使用。

---

## Contribution / 贡献

- **Suggestions / 建议**：如果有改进意见，欢迎提交 Issue，我会视情况考虑。
- **Support / 支持**：如果觉得 XSafe 有帮助，欢迎支持项目。
- **Open to Collaboration / 欢迎合作**：目前 XSafe 是基础版，后续可能会开发更完善的版本。有兴趣合作的朋友可联系我。

---

XSafe is a hobby project and is not intended as a fully-fledged security product. It’s best suited for virtual environments and for fun purposes within controlled setups. Enjoy the hunt!

**XSafe 仅作为娱乐项目，不具备完整的安全产品功能。推荐在虚拟环境中使用，或作为辅助工具在受控场景中使用。祝您狩猎愉快！**

## Test

![20241026054855](https://raw.githubusercontent.com/kyxiaxiang/XSafe/refs/heads/main/png/20241026054855.png)![20241026054758](https://raw.githubusercontent.com/kyxiaxiang/XSafe/refs/heads/main/png/20241026054758.png)

![20241026054944](https://raw.githubusercontent.com/kyxiaxiang/XSafe/refs/heads/main/png/20241026054944.png)

![20241026055008](https://raw.githubusercontent.com/kyxiaxiang/XSafe/refs/heads/main/png/20241026055008.png)

![20241026055048](https://raw.githubusercontent.com/kyxiaxiang/XSafe/refs/heads/main/png/20241026055048.png)

![20241026055132](https://raw.githubusercontent.com/kyxiaxiang/XSafe/refs/heads/main/png/20241026055132.png)

![20241026055211](https://raw.githubusercontent.com/kyxiaxiang/XSafe/refs/heads/main/png/20241026055211.png)
