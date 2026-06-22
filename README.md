**企业介绍 PPT 设计 Skill**

`corporate-ppt-design` 是一套用于设计企业级演示文稿的 Codex Skill。

它不直接套用模板，而是按照：

```text
内容逻辑 → 页面结构 → 视觉风格 → 排版落地 → 检查交付
```

完成整套 PPT 设计。

**适用场景**

- 企业介绍
- 产品发布会
- 商业计划书
- 融资路演
- 科技方案汇报
- 年度工作汇报
- 品牌宣传
- 将 DOCX、PDF 或文字资料转换为 PPT

**核心能力**

- 分析演示目的、受众和使用场景
- 提炼核心观点和结论型标题
- 搭建完整的逐页叙事结构
- 提供科技蓝白、深蓝发布会、黑底工业、红白创新等视觉方向
- 根据内容选择产品矩阵、数据页、地图、时间轴等版式
- 制定字体、色彩、图片和组件规范
- 生成逐页图片素材提示词
- 检查文字溢出、图片裁切、数据一致性和视觉统一性
- 配合 Presentations Skill 创建可编辑的 PPTX

**文件结构**

```text
corporate-ppt-design/
├── SKILL.md                  # 核心设计流程
├── agents/openai.yaml        # Skill 展示与调用配置
└── references/
    ├── story-structures.md   # 不同 PPT 的叙事结构
    ├── visual-directions.md  # 视觉风格、配色与字体
    ├── slide-patterns.md     # 页面版式库
    └── qa-checklist.md       # 交付检查清单
```

**使用示例**

```text
使用 $corporate-ppt-design，将这份公司资料设计成一套
面向客户的 15 页科技蓝白企业介绍 PPT。
```

Skill 会先理解“讲什么、给谁看、希望对方记住什么”，再开始设计页面。
