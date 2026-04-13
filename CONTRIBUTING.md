# 贡献指南 🤝

感谢你对 Fund Operation Workflow 的关注！欢迎贡献代码、提示词模板、或运营 SOP。

---

## 📋 行为准则

- **专业严谨**：基金运营需要专业态度
- **合规第一**：所有内容必须符合金融监管要求
- **尊重多样性**：不同 MBTI 特质各有优势
- **建设性反馈**：提出问题的同时，欢迎提供解决方案建议

---

## 🚀 如何贡献

### 1. 报告问题 (Issues)

发现问题？请创建 Issue 并包含：
- 问题描述（清晰、具体）
- 工作流节点缺失或不当
- MBTI 匹配合理性讨论
- 合规风险点
- 提示词优化建议

### 2. 提交代码 (Pull Requests)

贡献代码前请：
1. Fork 本仓库
2. 创建功能分支 (`git checkout -b feature/AmazingFeature`)
3. 提交更改 (`git commit -m 'Add some AmazingFeature'`)
4. 推送到分支 (`git push origin feature/AmazingFeature`)
5. 创建 Pull Request

### 3. 贡献提示词模板

欢迎分享提示词模板：
- 基于 STAR+ 合规前置框架
- 针对具体子节点（如"文案创作"vs"路径设计"）
- 包含合规约束
- 提供使用示例

### 4. 优化 MBTI 匹配

改进 MBTI 特质与工作流节点的匹配：
- 提供理论依据
- 说明匹配理由
- 给出实际案例

---

## 📝 代码风格

### 提示词模板

```markdown
【角色定义】
你是一位 [专家角色]，擅长 [核心能力]。

【STAR 背景】
- 情境 (Situation)：[具体业务场景]
- 任务 (Task)：[核心任务]
- 行动 (Action)：[分析框架/方法论]
- 结果 (Result)：[预期目标]

【合规约束】
- 所有输出需符合公募基金销售合规要求
- 不得出现"保本""稳赚""预期收益"等违规表述
- 风险提示必须完整

【输入】
- [具体输入信息]

【输出要求】
- [格式要求]
- [质量标准]
- [交付物清单]
```

---

## 🔧 开发环境

### 前置要求

- OpenClaw v1.0+
- Python 3.8+（可选，用于脚本）
- Git

### 本地测试

```bash
# 克隆仓库
git clone https://github.com/lj22503/fund-operation-workflow.git

# 进入项目目录
cd fund-operation-workflow

# 在 OpenClaw 中测试技能
# 使用 /clawhub install local 命令安装本地技能
```

---

## ⚠️ 合规要求

**所有贡献必须遵守：**

- ❌ 不得推荐具体基金
- ❌ 不得承诺收益/保本
- ❌ 不得使用"稳赚""必涨""预期收益"等违规表述
- ✅ 必须包含风险提示
- ✅ 符合公募基金销售管理办法
- ✅ 符合广告法要求

---

## 📊 工作流节点说明

### 战略层（2 人）

| 角色 | MBTI | 职责 |
|------|------|------|
| 内部战略 | INTJ | 产品资源梳理、技术能力评估 |
| 外部战略 | ENFJ | 渠道资源梳理、合作伙伴对接 |

### 执行层（6 节点）

| 节点 | MBTI | 职责 |
|------|------|------|
| 收集 | ENFP | 广告投放数据、KOL 种草数据、舆情监控 |
| 归档 | ISTJ | 数据归档、文档模板、SOP 管理 |
| 策略 | INTP | 用户获取策略、转化策略、数据指标体系 |
| 实施 | ENTJ | 路径设计、文案创作、设计管理、产品功能 |
| 测试 | ISFJ | 功能自检、评审、灰度测试、上线验收 |
| 监控 | INFJ | 数据监控、用户反馈、用户调研 |

---

## 📖 资源

- [SKILL.md](SKILL.md) - 技能说明文档
- [STAR 框架](references/star-framework.md) - STAR+ 合规前置框架详解
- [MBTI 匹配](references/mbti-mapping.md) - MBTI 特质与工作流节点匹配
- [合规检查清单](references/compliance-checklist.md) - 合规检查清单
- [OpenClaw 文档](https://docs.openclaw.ai) - OpenClaw 官方文档

---

## 📄 许可证

本项目采用 [MIT 许可证](LICENSE)。

**Copyright (c) 2026 燃冰 (燃冰 & ant)**

详见 [LICENSE](LICENSE) 文件。

**简单来说：**
- ✅ 你可以自由使用、修改、分发、商用
- ✅ 需要保留原作者版权和许可证声明
- ❌ 不提供任何担保，使用风险自负

---

## 🙏 致谢

感谢所有为本项目做出贡献的开发者！

**特别感谢：**
- 基金运营从业者（实战经验）
- 合规审核者
- 提示词优化贡献者

---

## 📬 联系方式

- GitHub Issues: [提交问题](https://github.com/lj22503/fund-operation-workflow/issues)
- 邮箱：[联系作者](mailto:your-email@example.com)
