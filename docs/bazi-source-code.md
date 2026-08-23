# 八字排盘源码：四柱命理的 JavaScript 实现

八字排盘源码的核心任务，是把出生日期和时间转换为年、月、日、时四柱，并在此基础上生成十神、藏干、纳音、五行及大运等数据。本仓库提供了一个纯前端 JavaScript 示例，开发者可以直接查看输入、计算与界面输出之间的关系。

## 排盘数据流程

1. 接收出生日期、时间和性别等输入。
2. 根据日期与历法规则确定四柱干支。
3. 以日干为参照计算十神关系。
4. 查询各地支藏干、纳音和五行属性。
5. 按项目规则生成大运与流年数据。
6. 将结果渲染到浏览器页面。

阅读源码时，建议先从 `index.js` 了解页面输入和输出，再查看 `paipan.js` 的排盘逻辑，最后阅读 `astro.js`、`timezone.js`、`common.js` 与 `utils.js` 等辅助模块。

## 适合哪些开发者

- 学习 JavaScript 日期与历法计算
- 研究四柱八字的数据结构
- 制作八字排盘网页原型
- 验证十神、藏干或大运展示逻辑
- 为现有项目补充测试案例

## 获取完整源码

完整项目可从 [GitHub 仓库](https://github.com/masterai-top/Zhouyi-Divination-System-Source-Code) 下载。进入仓库后选择 **Code → Download ZIP**，或者使用 Git 克隆：

```bash
git clone https://github.com/masterai-top/Zhouyi-Divination-System-Source-Code.git
```

相关文档：[八字计算器开发](./bazi-calculator.md) · [四柱干支基础](./four-pillars-ganzhi.md) · [十神计算说明](./ten-gods.md)

