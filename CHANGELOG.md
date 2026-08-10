# CHANGELOG — STRATRONIX 产品资料库

All notable changes to this repository are documented here.

## [2.0.0] — 2026-08-10

### Changed
- **重大更新**：替换中英两版说明书为 v2.0 完整版（14 章节）
- 删除旧版本：
  - `STA-100-Quick-Start-Guide-Chinese-v1.0.pdf`（85×80mm 印刷版，只有第一部分）
  - `STA-100-PAA-Product-Introduction-English-v1.pdf`（1.2MB 产品介绍）
- 上传汪总提供的最新源文档：
  - `STA-100-User-Manual-Chinese-v2.0.pdf`（2.5MB，14 章节完整版）
  - `STA-100-User-Manual-English-v2.0.pdf`（2.7MB，14 章节完整版）

### 14 章节覆盖
1. 设备介绍（包装/接口/规格）
2. 安装 OpenClaw 智能体框架（开机/API Key/网络）
3. Telegram/微信安装
4. 网页版 OpenClaw 后台控制
5. 关机
6. 输入法设置
7. 日常使用
8. 卸载
9. 密码设置
10. 锁屏设置
11. 保存聊天记录
12. 常见问题 (FAQ)
13. 使用注意事项
14. 大模型 LLM 参考

### Notes
- 仓库从空 README 状态升级为完整产品资料库
- 文件名采用 ASCII 命名（GitHub raw URL 不支持中文文件名）
- 配套二维码已更新（v2 中英两版 + 入口码）

---

## [1.0.0] — 2026-08-10 (已废弃)

### Added
- 中文说明书 PDF（85×80mm 印刷版）
- 英文产品介绍 PDF
- 中英双语 README
- GitHub Pages 主页
- 完整规格表

### Notes
- 仓库首版，仅作为快速参考；v2.0 为完整版（14 章节）
- v1.0 文件已在 v2.0 中删除

---

**版本管理规范**：
- `v1.x` — 说明书修订（内容更新、错别字修复、章节调整）
- `v2.x` — 大版本（产品形态变更、规格重大调整）
- `v3.x` — 重设计（视觉重做、品牌升级）

**PDF 文件命名规范**：
```
STA-100-{类型}-{语言}-{版本}.pdf
示例：
  STA-100-User-Manual-Chinese-v2.0.pdf
  STA-100-User-Manual-English-v2.0.pdf
  STA-100-Reference-Manual-Chinese-v1.0.pdf（待发布）
  STA-100-Quick-Start-Guide-Japanese-v1.0.pdf（待发布）
```