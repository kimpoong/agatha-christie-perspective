# Agatha Christie Perspective Skill

一个面向 Codex 的阿加莎·克里斯蒂推理创作与审稿 Skill。它从公开作品、访谈、档案与学术研究中提炼创作方法，重点处理：

- 真相账本与因果闭环
- 公平线索和双重解释
- 红鲱鱼与注意力误导
- 封闭空间及嫌疑人群像
- 调查者、叙述视角与终局揭示
- 小说、舞台剧等媒介之间的重构

## 安装

```bash
git clone https://github.com/kimpoong/agatha-christie-perspective.git
cp -R agatha-christie-perspective ~/.codex/skills/
```

安装后可以这样调用：

```text
使用 $agatha-christie-perspective 审查我的谜案大纲，检查真相账本、公平线索、误导与终局回收。
```

也可以说：“用阿婆的方法审查这篇小说的线索公平性。”

## 质量

- 五个核心心智模型
- 九条决策启发式
- 女娲静态检查 6/6 通过
- 独立保真评分 96/100（A 级）

详见 [`FIDELITY.md`](FIDELITY.md)。

## 目录

```text
SKILL.md                  # Skill 入口与执行工作流
agents/openai.yaml        # Codex UI 元数据
references/synthesis.md   # 框架提炼结果
references/research/      # 六维来源调研底稿
scripts/quality_check.py  # 静态质量检查
FIDELITY.md               # 独立保真评分
```

## 边界

这是基于公开资料重构的创作方法顾问，不代表阿加莎·克里斯蒂本人或其遗产管理方，也不生成冒充本人创作的“失落新作”。Skill 只迁移高层叙事机制，不收录小说全文，不复刻可识别段落，并对时代性偏见及危险知识设置了明确限制。

## 来源与生成

调研来源及证据等级保存在 `references/research/`。本 Skill 由[女娲 · Skill造人术](https://github.com/alchaincyf/nuwa-skill)流程生成并经过独立验证。

