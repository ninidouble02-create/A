# My Life OS v3.6.2

Home Screen Stability 版。

重点修复：
- 移除 Service Worker 页面缓存，避免 Safari 与桌面版反复加载旧脚本。
- 桌面启动地址统一为站点根路径。
- Habit 详情页直接提供“删除习惯”，不再依赖编辑页底部。
- 仅真正的 JavaScript 运行错误才显示脚本异常，资源加载失败不再误报。
- 数据键仍为 `mylife-v1-data`，不会主动清除本地数据。

注意：iPhone Safari 与“添加到主屏幕”的 Web App 可能拥有独立的网站数据容器。若首次打开桌面版看不到 Safari 里的旧数据，需要在 Safari 版导出本地备份，再在桌面版导入一次。之后桌面版会继续保存自己的本地数据。
