# 安全策略 / Security Policy

本文件适用于 AKFamily 组织下的所有仓库；仓库自带 `SECURITY.md` 的，以仓库内的为准。

## 支持的版本

只有各项目在 PyPI 上的**最新版本**会收到安全修复，请先升级到最新版本再确认问题是否仍然存在：

```bash
pip install akshare akquant aktools --upgrade
```

## 报告安全漏洞

**请不要在公开的 issue、PR 或讨论区报告安全漏洞。**

请通过 GitHub 的私密漏洞报告提交：打开对应仓库的 **Security** 标签页，点击 **Report a vulnerability**，例如：

- AKShare：<https://github.com/akfamily/akshare/security/advisories/new>
- AKQuant：<https://github.com/akfamily/akquant/security/advisories/new>
- AKTools：<https://github.com/akfamily/aktools/security/advisories/new>

报告中请尽量包含：受影响的项目与版本、问题描述、复现步骤或概念验证代码，以及可能造成的影响。

我们会在 7 天内确认收到，并在修复发布后公开安全公告；如你愿意，公告中会致谢报告者。

## 不属于安全漏洞的问题

以下问题请通过普通 issue 反馈：

- 数据接口报错或返回的数据有误（通常是数据源网站改版所致）
- 依赖库的一般性升级需求
- 与安全无关的功能建议

---

## Reporting a vulnerability (English)

Only the **latest release** of each project on PyPI receives security fixes.

**Please do not report security vulnerabilities through public issues, pull requests or discussions.** Use GitHub's private vulnerability reporting instead: open the **Security** tab of the affected repository and click **Report a vulnerability**. Include the affected project and version, a description, steps to reproduce or a proof of concept, and the potential impact.

We aim to acknowledge reports within 7 days and will publish a security advisory once a fix is released, crediting the reporter if they wish.
