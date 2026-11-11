# 乔布斯式产品审美 Skill

一个可移植的产品设计 Skill，把苹果设计规范、乔布斯公开表达、工业设计史和设计评审方法整理成软件与硬件都能使用的工作流。

它关注的是产品原则：明确目的、聚焦、删减、软硬件整合、细节工艺、可访问性、长期质量和有证据的取舍。它不复制 Apple 的视觉皮肤，也不是 Apple 官方材料或 Steve Jobs 本人发布的内容。

## 适用场景

- 产品方向、PRD、功能取舍和路线图评审
- Web、移动端、桌面端、穿戴设备和空间计算界面
- 工业设计、实体交互、包装、开箱和软硬件协同
- 设计系统、交互流程、状态设计、文案、动效、声音和无障碍
- 需要“极简但不空洞”“高级但不装饰化”“艺术品般完整”的设计评审

## 使用方式

将本目录放入任意支持 Agent Skills 的技能目录，然后显式调用：

```text
$jobs-aesthetic-product-design
```

也可以直接提出“用乔布斯式产品审美评审这个方案”“按极致审美原则重做这个界面”等请求，让支持自动发现的 Agent 选择它。

本仓库对应的全局安装位置为：

- Codex：`~/.codex/skills/jobs-aesthetic-product-design/`
- Cursor：`~/.cursor/skills/jobs-aesthetic-product-design/`

安装后重启对应应用，让技能索引刷新。

## 包内容

```text
jobs-aesthetic-product-design/
├── SKILL.md                         # Skill 入口与工作流
├── agents/openai.yaml               # Codex UI 元数据
├── references/
│   ├── 苹果设计规范.md                # 官方 HIG 与跨媒介迁移
│   ├── 乔布斯公开原则.md              # 可核对来源与设计推论
│   └── 极致审美评审.md                # 评分量表、测试和输出模板
├── README.md
└── LICENSE
```

## 资料边界

官方资料优先使用 Apple Developer 的 Human Interface Guidelines、Apple Design Resources、SF Symbols 和无障碍文档；乔布斯材料优先使用 Steve Jobs Archive、Smithsonian Institution 和 Stanford 的公开档案。设计史和社区文章用于补充背景与争议，不替代原始来源。

资料索引以 2026-11-11 为核对日期。Apple 的官方页面会随平台版本更新，使用时应打开链接查看最新规范。

## 许可

本 Skill 的原创说明和整理内容以 MIT License 发布。引用的外部资料、Apple 设计资源、商标和媒体内容仍受其各自的版权、商标和使用条款约束；本仓库不重新分发 Apple 专有素材。
