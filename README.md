# dashboards · 个人数据面板集

基于个人健康与生活数据的可视化面板集合，发布于 GitHub Pages。

## 面板列表

| 面板 | 地址 | 说明 |
|---|---|---|
| 🏋️ 减脂追踪 | [fitness/](https://zhizhi2213.github.io/dashboards/fitness/) | 体重趋势、每日目标达成度、运动记录与 AI 建议；每日自动更新 |

## 数据与更新流程

数据链路：`iPhone HealthKit → HealthMirror app → iCloud → 本地镜像 → data.json → 面板`

- 减脂面板的脱敏公开版由 `agent-md` 仓库中的 `publish.py` 生成（体重仅展示相对变化，不含绝对数值与 BMI）
- 本仓库 Git 历史即各期数据快照

## 新增面板

在根目录建子目录放 `index.html`，然后在门户页 `index.html` 的卡片列表里加一个 `<a class="item">` 即可。
