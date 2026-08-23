# 周易源码部署指南：本地运行与静态网站发布

本项目以 HTML、CSS 和 JavaScript 为主，可以作为静态网站运行，不需要数据库。下载源码后即可在本地查看，也可以发布到 GitHub Pages 或其他静态网站托管服务。

## 下载源码

打开 [项目 GitHub 仓库](https://github.com/masterai-top/Zhouyi-Divination-System-Source-Code)，点击 **Code → Download ZIP**，解压到本地目录。也可以运行：

```bash
git clone https://github.com/masterai-top/Zhouyi-Divination-System-Source-Code.git
cd Zhouyi-Divination-System-Source-Code
```

## 本地运行

可以直接打开 `index.html`。为避免浏览器对本地文件的限制，推荐启动静态服务器：

```bash
python -m http.server 8080
```

在浏览器访问 `http://localhost:8080`。部署前应分别测试桌面和移动设备，并检查页面脚本、图片和 `libs` 目录是否正常加载。

## GitHub Pages 发布

1. 将源码推送到自己的 GitHub 仓库。
2. 打开 **Settings → Pages**。
3. 在构建来源中选择从分支部署。
4. 选择包含 `index.html` 的分支和根目录。
5. 保存并等待 GitHub 生成访问地址。

## 上线检查

- 使用 HTTPS 访问
- 页面标题与说明准确描述项目
- 所有资源使用正确的相对路径
- 不在前端代码中保存密钥或私人数据
- 添加许可证、隐私说明和免责声明
- 用多个日期与时区案例验证排盘结果

其他文档：[周易源码概览](./zhouyi-source-code.md) · [八字计算器](./bazi-calculator.md) · [历法与时区](./chinese-calendar-timezone.md)

