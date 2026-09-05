# 资产生成执行表

## 生成顺序

| 批次 | 资产范围 | 数量 | 方法 | 验收重点 |
| --- | --- | ---: | --- | --- |
| P0-1 | A-01 至 A-06 阶段主视觉 | 6 | AI 生成 + 历史照片检索 | 年代差异清晰、构图可横向裁切 |
| P0-2 | B-01 至 B-06 地标首批 | 6 | 真实照片优先，缺失时 AI 重建 | 地标轮廓可识别、来源可追溯 |
| P0-3 | C-01 至 C-04 地图图层 | 4 | SVG 绘制 + GIS 参考 | 线条层级清楚、开关后有明显差异 |
| P0-4 | F-01 至 F-03 AI 抽象视觉 | 3 | AI 生成 | 深色底、青橙高亮、无文字 |
| P1 | A/B/C/D/E/F 剩余资产 | 45 | 混合 | 补齐章节叙事和细节 |
| P2 | G/H 与备用图 | 32 | SVG/设计制作 | 发布、纹理与替换安全 |

## AI 生成提示词模板

> A cinematic archival city scene of Shenzhen in **[year / phase]**, **[specific place or urban condition]**, viewed from **[camera angle]**, deep teal night palette with warm orange highlights, documentary realism blended with subtle graphic grid overlays, atmospheric haze, no logos, no readable text, no UI, 16:9 landscape composition, leave negative space on the left for interface copy.

## 每张图的执行字段

| 字段 | 内容 |
| --- | --- |
| Asset ID | 对应 `SZ-*` 编号 |
| 画面任务 | 这张图在页面中解释什么 |
| 事实约束 | 地点、年代、建筑和交通关系 |
| 生成/检索方式 | 真实照片、AI 生成或混合 |
| 版式安全区 | 左/右侧保留文字和渐变空间 |
| 颜色检查 | 深色底、青色系统高亮、橙色历史能量 |
| 版权记录 | 原始来源链接或生成记录 |
| 替代文本 | 供无障碍与搜索使用 |
| 状态 | brief / generating / review / approved |

## P0 逐张执行

| ID | 画面 brief | 页面用法 | 状态 |
| --- | --- | --- | --- |
| SZ-A-01-1980-origin | 1980 蛇口/罗湖外围，低密度聚落与深圳河 | Hero + Timeline | Placeholder |
| SZ-A-02-1992-accelerate | 1992 工业厂房、货运、人口流动 | Timeline | Placeholder |
| SZ-A-03-2004-connect | 机场、高速和口岸作为城市接口 | Timeline + Compare | Placeholder |
| SZ-A-04-2010-expand | 大运会公共空间与新交通 | Timeline | Placeholder |
| SZ-A-05-2018-network | 科技园、湾区和夜间海岸线 | Timeline + Footprint | Placeholder |
| SZ-A-06-2024-future | 超大城市绿色/数字基础设施 | Hero + Compare | Placeholder |
| SZ-B-01-shekou-then | 蛇口工业区早期档案 | Landmark | Placeholder |
| SZ-B-02-luohu-then | 罗湖口岸历史场景 | Landmark | Placeholder |
| SZ-B-03-guomao-then | 国贸大厦建设期 | Landmark | Placeholder |
| SZ-B-04-huaqiangbei-then | 华强北电子市场早期 | Landmark | Placeholder |
| SZ-B-05-civic-center-now | 市民中心公共界面 | Landmark | Placeholder |
| SZ-B-06-super-hq-now | 深圳湾超级总部滨水界面 | Landmark | Placeholder |
| SZ-C-01-coastline | 深圳湾岸线与城市边缘 | Footprint | Placeholder |
| SZ-C-02-shenzhen-river | 深圳河作为边界和水系 | Footprint | Placeholder |
| SZ-C-03-rail-port | 铁路、口岸与东西向连接 | Footprint | Placeholder |
| SZ-C-04-metro | 轨道网络扩张 | Footprint | Placeholder |
| SZ-F-01-origin-abstract | 参考图风格的起点网格/光晕 | Hero | Placeholder |
| SZ-F-02-grid-accelerate | 产业与人口高速汇聚的抽象图 | Timeline | Placeholder |
| SZ-F-03-network-glow | 创新走廊与湾区网络光路 | Compare | Placeholder |
