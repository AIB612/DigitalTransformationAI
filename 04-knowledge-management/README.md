# 🧠 企业知识管理 | Enterprise Knowledge Management

> By SherryAGI | AI 驱动的企业内部知识库 (KI-gestützte Wissensdatenbank)

---

## 📚 模块内容

| 文件 | 内容 | 难度 |
|------|------|------|
| [01-rag-basics.ipynb](./01-rag-basics.ipynb) | RAG 基础架构 | ⭐⭐ |
| [02-document-processing.ipynb](./02-document-processing.ipynb) | 文档处理与分块 | ⭐⭐⭐ |
| [03-vector-search.ipynb](./03-vector-search.ipynb) | 向量检索实现 | ⭐⭐⭐ |
| [04-enterprise-kb.ipynb](./04-enterprise-kb.ipynb) | 企业知识库搭建 | ⭐⭐⭐⭐ |

---

## 🎯 业务价值

| 场景 | 传统方式 | RAG 方式 |
|------|----------|----------|
| 查找文档 | 手动搜索，耗时 | 自然语言提问，秒级响应 |
| 新员工培训 | 阅读大量文档 | AI 问答，按需学习 |
| 经验传承 | 依赖老员工 | 结构化存储，永久可用 |
| 跨部门协作 | 信息孤岛 | 统一知识库，全员共享 |

---

## 🏗️ RAG 架构

```
┌─────────────────────────────────────────────────────┐
│                  企业知识管理系统                      │
├─────────────────────────────────────────────────────┤
│  📄 文档层        │  🔍 检索层       │  🤖 生成层     │
│  ─────────────   │  ─────────────  │  ───────────  │
│  PDF/Word/PPT    │  向量数据库      │  LLM 生成     │
│  Markdown        │  语义搜索        │  答案合成     │
│  数据库记录       │  混合检索        │  来源引用     │
└─────────────────────────────────────────────────────┘
```

---

## 🛠️ 推荐开源工具

### RAG 框架
| 工具 | 特点 | 链接 |
|------|------|------|
| **RAGFlow** | 专业 RAG 引擎 | github.com/infiniflow/ragflow |
| **Dify** | 低代码 AI 平台 | github.com/langgenius/dify |
| **AnythingLLM** | 一体化桌面应用 | github.com/Mintplex-Labs/anything-llm |
| **Langchain-Chatchat** | 中文本地知识库 | github.com/chatchat-space/Langchain-Chatchat |

### 向量数据库
| 工具 | 特点 | 适用场景 |
|------|------|----------|
| **pgvector** | PostgreSQL 扩展 | 已有 PG 基础设施 |
| **Milvus** | 高性能向量库 | 大规模生产环境 |
| **Chroma** | 轻量级嵌入式 | 快速原型开发 |
| **Qdrant** | Rust 高性能 | 云原生部署 |

---

## 🇨🇭 瑞士合规部署

```yaml
# 数据驻留要求
data_residency: Switzerland
encryption: AES-256
compliance:
  - FADP (联邦数据保护法)
  - GDPR
  - SOC2 (可选)
  
# 推荐部署方式
deployment:
  - Azure Switzerland North
  - Swisscom Cloud
  - 本地私有化部署
```
