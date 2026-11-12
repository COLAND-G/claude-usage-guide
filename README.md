# Claude 使用说明

## 简介

Claude 是 Anthropic 开发的 AI 助手，提供多种产品形态来满足不同的使用场景。

## 产品形态

### 1. Claude.ai 网页版
- **访问地址**: https://claude.ai
- **适用场景**: 日常对话、文档分析、写作辅助
- **特点**: 无需安装，浏览器直接使用

### 2. Claude Code CLI
- **介绍**: Anthropic 官方命令行工具
- **底层模型**: Claude Opus 5.5
- **适用场景**: 代码开发、项目管理、自动化任务
- **主要功能**:
  - 文件读写和编辑
  - 执行终端命令
  - 代码审查和调试
  - Git 操作集成

### 3. Claude API
- **文档**: https://docs.anthropic.com
- **适用场景**: 应用集成、自动化工作流
- **可用模型**:
  - Claude Opus 5.5 (最强大)
  - Claude Sonnet 5.5 (平衡性能)
  - Claude Haiku 5.5 (快速响应)
  - Claude Fable 5.2

## 使用技巧

### 提示词编写建议

1. **清晰明确**: 直接说明你的需求
2. **提供上下文**: 给出必要的背景信息
3. **分步骤**: 复杂任务可以分解成多个步骤
4. **提供示例**: 给出期望输出的样例

### Claude Code 常用命令

```bash
# 启动交互式会话
kiro-cli chat

# 执行单次任务
kiro-cli ask "你的问题"

# 查看帮助
kiro-cli --help
```

### 最佳实践

1. **代码开发**
   - 让 Claude 先阅读相关文件
   - 明确指定要修改的功能
   - 要求运行测试验证更改

2. **文档分析**
   - 上传或提供文档内容
   - 具体说明需要提取的信息
   - 可以要求特定格式的输出

3. **写作辅助**
   - 说明文档类型和目标受众
   - 提供大纲或关键点
   - 可以要求多种风格选择

## 安全和隐私

- Claude 遵守严格的隐私政策
- 对话数据用于改进服务（可选择退出）
- 不应输入敏感的个人信息或机密数据
- API 调用遵循您的数据保留政策

## 限制和注意事项

1. **知识截止日期**: Claude 的训练数据有时间限制
2. **实时信息**: 无法直接访问互联网获取实时信息
3. **文件大小**: 上传文件有大小限制
4. **速率限制**: API 调用有频率限制

## 资源链接

- [官方网站](https://www.anthropic.com)
- [API 文档](https://docs.anthropic.com)
- [社区论坛](https://community.anthropic.com)
- [定价信息](https://www.anthropic.com/pricing)

## 常见问题

### Q: Claude 和 ChatGPT 有什么区别？
A: Claude 由 Anthropic 开发，注重安全性和有用性，在长文本理解和代码生成方面表现出色。

### Q: Claude Code 是免费的吗？
A: Claude Code 需要 Anthropic API 密钥，按使用量计费。

### Q: 如何获取 API 访问权限？
A: 访问 https://console.anthropic.com 注册账户并申请 API 密钥。

### Q: Claude 支持哪些语言？
A: Claude 支持多种语言，包括中文、英文、日文、韩文、西班牙文、法文等。

---

**更新日期**: 2026-11-12

**贡献**: 欢迎提交 Issue 和 Pull Request 来改进此文档。
