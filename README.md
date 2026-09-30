# Reference 非官方镜像站

本项目是 [jaywcjlove/reference](https://github.com/jaywcjlove/reference) 的静态镜像站，旨在为国内开发者提供一个稳定、快速的访问入口。

## 📖 关于原项目

原项目 [Reference](https://github.com/jaywcjlove/reference) 是由 [小弟调调™ (jaywcjlove)](https://github.com/jaywcjlove) 开发的一款为开发者提供快速参考备忘清单的开源知识库。它涵盖了 JavaScript、Docker、Linux、C++ 等大量技术栈的速查表，是日常开发中非常实用的工具。

原作者对镜像站的部署持开放和支持态度，特此向原作者的辛勤付出致敬！

## ⭐ 支持原作者

如果您觉得这个项目对您有帮助，**请务必前往原项目点一个 ⭐️ Star**，这是对原作者最大的鼓励与支持！

*   **原项目地址**：https://github.com/jaywcjlove/reference
*   **原作者 GitHub**：https://github.com/jaywcjlove

## 🛠️ 仓库说明

本仓库仅用于镜像站的自动化同步与部署，具体结构如下：

*   **`main` 分支**：存放 GitHub Actions 自动同步脚本，负责定时从原仓库拉取最新的 `gh-pages` 分支内容。
*   **`gh-pages` 分支**：存放原项目构建好的静态网站文件，由 Cloudflare Pages 自动拉取并部署。
*   **部署平台**：Cloudflare Pages

## 📄 许可证

本项目遵循原项目的 **MIT 许可证**。镜像站仅用于学习与交流，所有内容版权归原作者所有。

---
*本仓库为第三方非官方镜像站，与原项目无直接隶属关系，请以原项目为准。*
