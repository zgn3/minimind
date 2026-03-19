# MiniMind 复现项目

## 项目简介
基于 PyTorch 和 Transformers 复现轻量级 LLM 项目 MiniMind，完成环境搭建、代码阅读与 GitHub 工程化管理。

## 主要内容
- 配置 Python 3.13 + uv + conda 开发环境
- 跑通项目依赖安装与版本管理
- 阅读并复现模型配置与训练代码
- 使用 Git/GitHub 管理项目版本

## 项目结构
- `model/`: 模型结构与配置
- `trainer/`: 训练相关代码
- `dataset/`: 数据处理
- `main.py`: 主入口

## 运行方式
```bash
uv sync
python main.py
