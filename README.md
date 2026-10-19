# MOSS 控制台 · 全新 UI

为本地 AI Agent 应用 MOSS 控制台（流浪地球 550W 题材）设计的全新深色工业风 UI。

## 设计主张

**让操作员在三秒内判断：MOSS 现在安全吗？**

- 深蓝黑底（#0B0F16）替代原纯黑 + CRT 扫描线
- MOSS 红（#E8443A）收敛为唯一高饱和色，只在危险/待审批处出现
- 默认首屏为总览 Dashboard：引擎状态 / 进行中会话 / 工具调用 / 待审批 四张 KPI
- 对话、轨迹审计为独立视图
- 授权弹窗保留 AUTHORIZATION REQUIRED 叙事，列出工具、路径、风险等级

## 使用

直接在浏览器打开 `index.html` 即可预览。
替换 Electron 应用原前端 `resources/app/public/console.html` 即可作为默认皮肤。

## 配色

| 角色 | 值 |
|---|---|
| 深空底 | `#0B0F16` |
| 面板 | `#131A26` |
| MOSS 红 | `#E8443A` |
| 仪表金 | `#E8B34B` |
| 在线青绿 | `#4ED09A` |

设计方案文档：https://my.feishu.cn/docx/BJkcd24ZzoTM1exsJmocVGYn6ah
