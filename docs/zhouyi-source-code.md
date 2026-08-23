# 周易源码：JavaScript 八字排盘项目说明

本项目是一套可以在浏览器中运行的周易源码，主要用于八字排盘、干支历法与传统命理数据的学习和开发。源码采用 HTML、CSS 和 JavaScript 编写，不依赖数据库，适合希望了解四柱排盘实现方式的开发者。

## 源码包含什么

- 年柱、月柱、日柱和时柱排盘
- 天干、地支、阴阳与五行数据
- 十神、藏干和纳音展示
- 大运、流年与换运时间展示
- 日期、时区及相关工具模块
- 可直接查看和修改的前端界面

仓库中的 `index.html` 是页面入口，`index.js` 负责主要交互，`paipan.js`、`astro.js`、`timezone.js` 等文件承载排盘、历法和时区相关逻辑。

## 下载与运行

前往 [Zhouyi Divination System Source Code](https://github.com/masterai-top/Zhouyi-Divination-System-Source-Code)，点击 **Code → Download ZIP** 下载完整源码。解压后打开 `index.html`；如果浏览器限制本地资源，可在项目目录运行：

```bash
python -m http.server 8080
```

然后访问 `http://localhost:8080`。

## 使用前需要确认

八字排盘可能因节气边界、子时换日、时区和真太阳时规则不同而产生差异。用于正式产品前，应当明确采用的规则，并用可靠案例测试边界日期。

继续阅读：[八字源码说明](./bazi-source-code.md) · [项目部署指南](./deployment-guide.md) · [历法与时区](./chinese-calendar-timezone.md)

> 本项目用于传统文化、历法算法和软件开发交流，输出结果不构成现实决策建议。

