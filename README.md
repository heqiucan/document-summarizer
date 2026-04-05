# 文档摘要生成器 (Document Summarizer)

基于大模型 API 的命令行工具，读取本地 txt 文件，自动生成摘要。解决长文本超出 API token 限制的问题（通过文本分块+合并）。

## 功能
- 支持命令行参数指定文件：`python summary_generator.py sample.txt`
- 自动读取文件内容，调用大模型 API 生成简洁摘要
- （待实现）长文本自动分块 + 向量检索 → RAG 完整版

## 技术栈
- Python 3
- Requests / OpenAI API（根据实际使用的库调整）
- 命令行参数解析（sys.argv）

## 快速开始

1. 安装依赖：
   ```bash
   pip install requests
