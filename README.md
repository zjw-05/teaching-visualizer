# teaching-visualizer v0.1

一份面向初中电学家教的可复用 Skill：用“讲一点 → 先猜 → 动手/判断 → 验证 → 总结”帮助学生解释电学结论背后的因果过程。

## 交互教学

打开[电学原理实验室](index.html)，在三个专题之间切换，先预测，再操作电路或滑片查看反馈。网页为单文件、无依赖实现：克隆仓库后可直接用浏览器打开 `index.html`，也可通过 GitHub Pages 发布。

## 内容

- [`SKILL.md`](SKILL.md)：Skill 指令。
- [`lessons/01-current.md`](lessons/01-current.md)：电流怎样形成。
- [`lessons/02-series-parallel.md`](lessons/02-series-parallel.md)：串联与并联的判断。
- [`lessons/03-rheostat.md`](lessons/03-rheostat.md)：电阻与滑动变阻器。

## 使用方法

将 `SKILL.md` 放入支持 Agent Skills 的技能目录，或在支持技能的工具中加载它。给出年级、知识点、已有器材和课时后，按 Skill 的输出格式生成一页讲解和一项验证活动。

## 教学边界

材料采用初中常见理想化模型；实际亮度受电池、灯泡、接线和接触状态影响。短路只用图示讨论，不让学生实接。滑动变阻器的变化方向必须结合接入的端子判断。

## License

MIT，见 [`LICENSE`](LICENSE)。
