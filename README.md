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

### Week 2 — Prompt & Ollama

| 檔案 | 主題 |
|------|------|
| `week2/1_Prompt.ipynb` | Prompt 基礎 |
| `week2/2_Ollama.ipynb` | 使用 Ollama 本地模型 |

### Week 3 — 語意搜尋、RAG 與 Context Engineering

| 檔案 | 主題 |
|------|------|
| `week3/1_用_Python_實作語意搜尋_教學版.ipynb` | 用 Python 實作語意搜尋 |
| `week3/2_徒手實作簡化版的_RAG_教學版.ipynb` | 徒手實作簡化版 RAG（使用 Groq llama-3.3-70b + multilingual-e5-small） |
| `week3/3_Context Engineering.ipynb` | Context Engineering |
| `week3/4_HW1.ipynb` | 作業 1 |

### Week 4 — RAG 進階與 Rerank

| 檔案 | 主題 |
|------|------|
| `week4/1_RAG_KnowledgeSample.ipynb` | RAG 知識庫範例 |
| `week4/2_Rerank.ipynb` | Rerank 重排序 |
| `week4/3_HW2.ipynb` | 作業 2 |

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
├── week2/
│   ├── 1_Prompt.ipynb
│   └── 2_Ollama.ipynb
├── week3/
│   ├── 1_用_Python_實作語意搜尋_教學版.ipynb
│   ├── 2_徒手實作簡化版的_RAG_教學版.ipynb
│   ├── 3_Context Engineering.ipynb
│   └── 4_HW1.ipynb
├── week4/
│   ├── 1_RAG_KnowledgeSample.ipynb
│   ├── 2_Rerank.ipynb
│   └── 3_HW2.ipynb
├── pyproject.toml
├── uv.lock
└── README.md
```
