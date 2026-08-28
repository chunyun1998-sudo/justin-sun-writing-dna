# 孙割小长文版写作风格 (sunge-narrative-style)

> 基于 Justin Sun (孙宇晨) X 长文《我的女友景甜》的写作 DNA 蒸馏与风格复刻 skill

## 这是什么

这是一个 [writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill) 的蒸馏产物，从孙宇晨 2026-08-27 发布的 X Article 长文《我的女友景甜》中提取写作风格规则，形成可复用的 Agent Skill。

## 风格核心

**用极短句和一句一段的碎片化叙事，在对话和物件中传递情感，绝不直接描写情绪。数字是情感锚点，沉默是叙事语言，留白是节奏本身。**

关键数据：

| 指标 | 数值 |
|------|------|
| 平均句长 | 14 字 |
| 短句(≤15字)占比 | 63% |
| 长句(≥50字)占比 | 0% |
| 一句一段占比 | 69% |
| 平均段落字数 | 24 字 |

## 仓库结构

```
justin-sun-writing-dna/
├── SKILL.md                          # Agent Skill 本体
├── Justin-Sun/
│   ├── raw/                          # 原始文章语料
│   │   └── 2026-08-27-叙事散文-我的女友景甜-X-Article.md
│   ├── _meta/                        # 元数据
│   │   └── 2026-08-27-我的女友景甜.json
│   ├── 语言DNA.md                    # L1 表层语言分析
│   ├── 文章结构模板.md               # L2 结构模板
│   ├── 写作视角与认知框架.md         # L3-L5 选题/素材/认知
│   ├── 视觉风格指南.md               # L6 视觉风格
│   └── Writing-DNA.md               # 整合文档
```

## 使用方式

### 安装为 Agent Skill

将 `SKILL.md` 放入你的 skills 目录：

```bash
# ~/.agents/skills/ (跨 Agent 平台)
mkdir -p ~/.agents/skills/sunge-narrative-style
cp SKILL.md ~/.agents/skills/sunge-narrative-style/
```

### 触发词

- "用孙割风格写"
- "按孙宇晨风格写一篇"
- "孙割小长文"

## 蒸馏层次

| 层次 | 产物 | 内容 |
|------|------|------|
| L1 表层语言 | 语言DNA.md | 词频、句长、标点、修辞 |
| L2 文章结构 | 文章结构模板.md | 三幕+尾声结构模板 |
| L3 选题逻辑 | 写作视角与认知框架.md | 选题判断标准 |
| L4 素材策略 | 写作视角与认知框架.md | 素材类型与使用原则 |
| L5 认知框架 | 写作视角与认知框架.md | 五条核心命题 |
| L6 视觉风格 | 视觉风格指南.md | 排版、留白、色彩 |

## 重要说明

- ⚠️ 本仓库基于**单篇文章**蒸馏，为演示版 DNA，不代表作者完整风格全貌
- 原文作者声明「不设版权，请随意转发分享」
- 蒸馏产物（语言DNA、结构模板等）以 MIT 许可证开源
- 本仓库用于学习、分析和风格研究，不用于冒充作者本人

## 致谢

- 原文作者：[H.E. Justin Sun](https://x.com/justinsuntron)
- 蒸馏工具：[writing-dna-skill](https://github.com/larashero3-dotcom/writing-dna-skill)

## License

MIT License
