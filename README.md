# Surge Icons Repository

自定义 Surge 策略组图标仓库 / Custom Surge Policy Icons Repository

## 📁 目录结构 / Directory Structure

```
icons/
├── ai/          # AI 服务图标 (Claude, ChatGPT, Gemini, etc.)
├── streaming/   # 流媒体服务图标 (Netflix, Disney+, etc.)
├── companies/   # 公司品牌图标 (Apple, Google, Microsoft, etc.)
└── system/      # 系统图标 (Proxy, Direct, etc.)
```

## 🎨 使用方法 / Usage

在 Surge 配置文件中使用以下格式引用图标：

```
[Proxy Group]
🤖 AI_Claude = select, 🇺🇸 US_Node, policy-icon-url=https://raw.githubusercontent.com/lanbipu1988/surge-icons/main/icons/ai/claude.png
```

## 📝 图标列表 / Icon List

### AI 服务 / AI Services
- `icons/ai/claude.png` - Anthropic Claude
- `icons/ai/chatgpt.png` - OpenAI ChatGPT
- `icons/ai/gemini.png` - Google Gemini
- `icons/ai/copilot.png` - Microsoft Copilot

### 流媒体 / Streaming
- `icons/streaming/netflix.png` - Netflix
- `icons/streaming/disney.png` - Disney+
- `icons/streaming/youtube.png` - YouTube

### 公司品牌 / Companies
- `icons/companies/apple.png` - Apple
- `icons/companies/google.png` - Google
- `icons/companies/microsoft.png` - Microsoft
- `icons/companies/telegram.png` - Telegram
- `icons/companies/twitter.png` - Twitter/X

### 系统 / System
- `icons/system/proxy.png` - Proxy
- `icons/system/direct.png` - Direct

## 📌 注意事项 / Notes

1. 所有图标建议使用 PNG 格式，尺寸 108x108 或更高
2. 确保图标背景透明以获得最佳显示效果
3. 图标文件名使用小写字母和连字符

## 🔗 相关链接 / Links

- [Surge Manual](https://manual.nssurge.com/)
- [Surge Policy Icon Documentation](https://manual.nssurge.com/policy/group.html)

---

**License:** MIT
