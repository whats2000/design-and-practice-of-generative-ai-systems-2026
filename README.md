# 生成式 AI 系統設計與實踐 2026

## 簡介

本課程帶你從零開始，理解並實作生成式 AI 系統的核心技術，包括 RAG（檢索增強生成）等主題。

## 環境需求

- Python 3.11+
- [uv](https://github.com/astral-sh/uv)（套件管理工具）

## 快速開始

```bash
# 1. 建立虛擬環境並安裝相依套件
uv sync

# 2. 啟動 Jupyter Notebook
uv run jupyter notebook
```

## 課程列表

| 檔案 | 主題 |
|------|------|
| `2_徒手實作簡化版的_RAG_教學版.ipynb` | 徒手實作簡化版 RAG（使用 Groq llama-3.3-70b + multilingual-e5-small） |

## 使用模型

### LLM（生成模型）
- `llama-3.3-70b-versatile`（透過 [Groq](https://groq.com/) API）

### Embedding 模型
- `intfloat/multilingual-e5-small`（輸出維度：384）

## 環境變數

在根目錄建立 `.env` 檔案或在執行環境中設定：

```
GROQ_API_KEY=your_api_key_here
```

## 專案結構

```
.
├── 2_徒手實作簡化版的_RAG_教學版.ipynb   # RAG 教學 Notebook
├── pyproject.toml                        # 專案設定與相依套件
├── uv.lock                               # 鎖定套件版本
└── README.md
```
