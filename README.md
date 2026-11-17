# 盐译 Oneclear

Chrome MV3 网页翻译扩展。使用自己的模型服务（OpenAI 兼容 / Claude / Gemini 协议），按需翻译网页，支持双语、仅译文和一键恢复原文。

## 功能

- 网页双语 / 仅译文 / 恢复原文，`Alt+T` 切换翻译，`Alt+B` 切换模式
- 模型服务配置：DeepSeek、OpenAI、Claude、通义千问、Kimi、硅基流动、OpenRouter、Gemini 及自定义服务
- AI 专家角色：科技类、X 推文、Reddit，可自定义
- 翻译窗口：长文分段翻译与进度显示
- YouTube 字幕翻译（测试功能）

## 安装

1. 下载本仓库，保留 `dist/` 文件夹完整。
2. Chrome 地址栏打开 `chrome://extensions`，开启「开发者模式」。
3. 点击「加载已解压的扩展程序」，选择 `dist/` 文件夹。
4. 固定盐译到工具栏，在设置中添加模型服务和自己的 API Key。

## 说明

- 本仓库不包含任何 API Key、浏览历史或翻译缓存，密钥保存在本机 Chrome 存储中。
- 模型请求直接发送到所选服务商，不经过中间服务器。
- 字体及图标的开源许可见 `dist/licenses/` 和 `dist/THIRD-PARTY-NOTICES.txt`。
