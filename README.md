# 技术文档翻译项目

本项目使用 [babeldoc](https://github.com/funstory-ai/BabelDOC) 将技术文档翻译成中文。

## 项目概述

本项目将技术规范从英文翻译为中文，生成以下三种版本的 PDF 文档：

| 文件 | 说明 |
|------|------|
| `swra726.pdf` | 原版英文文档 |
| `swra726.zh.mono.pdf` | 纯中文翻译版本 |
| `swra726.zh.dual.pdf` | 中英对照版本（双栏布局） |

## 翻译版本说明

### 纯中文版本 (mono)
仅包含中文翻译内容，适合仅需中文阅读的场景。

### 对照版本 (dual)
采用双栏布局，左侧为英文原文，右侧为中文翻译，方便对照阅读和理解。

采用本地ollama翻译，命令行
babeldoc --openai --openai-model "qwen2.5:14b-instruct" --openai-base-url "http://localhost:11434/v1" --openai-api-key "your-api-key-here"  --files swra726.pdf --pool-max-workers 1
