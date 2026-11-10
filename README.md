# 鲸鱼投研台 · 静态快照

由本地 `whale-quant` 导出的单文件页面，每天收盘后自动更新。

- 只读：数据是导出那一刻的，不能搜索 / 实时刷新
- 交互：可以切股、切周期、切页签（研判台 / 推荐榜 / 持仓监测）

生成流程：`python tools/export_static.py` → `docs/whale-quant-snapshot.html` → `pages/index.html` → `git push`
