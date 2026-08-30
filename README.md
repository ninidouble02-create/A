# My Life OS v3.7.0 — Stability Rebuild

重点修复：iOS 主屏幕模式运行稳定性、Plan Pool 缺失函数、Health 生理期日历缺失、Habit/Food/Media 删除、页面恢复后自动重读本地数据、右上角更多菜单、双击误缩放。

数据键仍为 `mylife-v1-data`，升级不会主动清空原有 localStorage 数据。

注意：iOS Safari 网页与“添加到主屏幕”的 Web App 可能由系统分配不同的网站存储容器；若首次打开桌面 App 看不到 Safari 中已有数据，请先在 Safari 版“备份与恢复”导出，再在桌面 App 导入。之后桌面 App 内的数据会继续保存在本机。


v3.7.1: restored missing Life editor runtime, legacy-safe delete matching, cache bump for iOS Home Screen.


## v3.7.3 Dynamic Routine Layers
继续动态 Routine：为后续子 Routine（护肤、洗头、出门、打扫）加入兼容层；保留 v3.7.2 出现条件；返回前台自动刷新 Today；改善 iPhone 双击缩放。


## v3.7.6 Child Routine UI
子 Routine 正式进入可操作界面：Routine 执行页每个步骤可点击“🌿 子 Routine”选择另一个 Routine；关联后步骤内显示子流程卡片并可直接进入执行。编辑父 Routine 时会保留关联，不会因保存步骤文本而丢失。子 Routine 无需单独出现在 Today。
