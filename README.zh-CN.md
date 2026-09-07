# NoveMD

<p align="center">
  <img src="assets/novemd-icon.png" width="180" alt="NoveMD 图标">
</p>

<p align="center"><strong>面向本地写作、文档转换、高质量导出与演示的 Markdown 工作台。</strong></p>

<p align="center">简体中文 · <a href="README.md">English</a></p>

NoveMD 是一款专有的 Windows 桌面软件。本公开仓库仅作为 NoveMD 的 GitHub 官方下载与版本信息渠道，**不包含软件源代码**。

## NoveMD 的亮点

- **本地优先：** 文档、设置、备份和历史默认保存在你的电脑上；NoveMD 不会为了云存储、广告或产品分析上传文档正文。
- **两种编辑视图、三种布局：** 可在文档视图和源码视图之间切换，根据写作、文件管理或专注阅读选择布局；阅读时可以直接打开链接。
- **导入已有资料：** 可将 Word、PowerPoint、Excel、OpenDocument、RTF、EPUB、CSV、文本型 PDF 和受支持的韩文文档转换成可编辑 Markdown。
- **导出适合交付的文件：** 支持 TXT、PDF、带样式 HTML、干净 HTML、DOCX、演示 HTML、PPTX 和 LaTeX；离线阅读包可保留 Markdown 结构、链接及本地可用图片。
- **更可靠的图片与链接：** 支持远程图片加载和本地缓存、HTML 图片内嵌，并针对常见 Office/PDF 阅读器持续优化图片尺寸、链接保留和文档排版兼容性。
- **Markdown 演示：** 可从 Markdown 创建或预览演示文稿，并导出浏览器演示和 PowerPoint 文件。
- **十种界面语言：** 简体中文、繁体中文、英语、日语、韩语、西班牙语、俄语、德语、法语和巴西葡萄牙语。

默认安装包不包含扫描型或纯图片 PDF 的 OCR。面对复杂第三方格式、特殊字体或正式交付文件，仍建议在目标软件中完成最终检查。

## 下载

当前公开版本为 **NoveMD 2.0.11**，适用于 **Windows 10/11 64 位系统**。

- [从 NoveMD 官方网站下载](https://buer.store/download)
- [从 GitHub Releases 下载](../../releases/latest)
- [查看 2.0.11 版本说明](releases/v2.0.11.md)

目前安装包尚未进行代码签名，Windows SmartScreen 可能显示“未知发布者”。请只从官方网站或本仓库下载，并核对 Release 同时提供的 SHA-256 校验值。

在 PowerShell 中核验：

```powershell
Get-FileHash -Algorithm SHA256 -LiteralPath '.\NoveMD.Setup.2.0.11.exe'
```

正确的 SHA-256：

```text
FFA9E1C93D707C125A9381FFA6F7AA6B51FD3C2266356A2AA663433CAC0F3B41
```

## 试用与授权

- 提供 30 天全功能试用。
- 试用结束后仍可打开、阅读和导出已有文档；继续编辑需要有效授权。
- 一次购买、永久使用，不是订阅制，不会自动续费。
- 不同销售地区的一次性价格会在官网购买页和结账页中显示，付款前可以确认实际币种和金额。
- 一份授权最多可在授权持有人的两台设备上激活。
- 首次激活需要联网，激活后日常使用可以离线进行。

当前价格、币种和购买条件以 [buer.store](https://buer.store) 针对相应销售地区实际显示的内容为准。

## 隐私、条款与支持

- [隐私政策](https://buer.store/privacy)
- [服务条款](https://buer.store/terms)
- [退款政策](https://buer.store/refund)
- [支持和问题反馈](SUPPORT.md)
- [安全问题报告](SECURITY.md)
- [专有软件声明](LICENSE.txt)
- [第三方软件声明](THIRD_PARTY_NOTICES.md)

请勿在公开 GitHub Issue 中发布激活码、订单资料、私人文档、邮箱地址或安全敏感信息。

## 关于源代码

NoveMD 是闭源商业软件。GitHub 在 Release 页面自动生成的 “Source code” 压缩包只包含本下载仓库中的公开说明文件，不包含 NoveMD 应用程序源码。
