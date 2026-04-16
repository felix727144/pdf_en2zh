# 技术文档翻译项目

本项目使用 [babeldoc](https://github.com/NaiboWang/babeldoc) 将技术文档翻译成中文。

## 项目概述

本项目将 3GPP TR 26.930 (3GPP TSG-SA Working Report on Multi-stream NAT) 技术规范从英文翻译为中文，生成以下三种版本的 PDF 文档：

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

## 使用方法

1. 访问 babeldoc 网站或仓库获取 babeldoc 工具
2. 配置翻译选项为目标语言中文
3. 输入源 PDF 文档进行翻译
4. 选择输出格式（纯中文或对照版本）

## 文件大小

- 原始文档: ~3.2 MB
- 对照版本: ~6.8 MB (51 pages)
- 纯中文版本: ~3.6 MB (10 pages)