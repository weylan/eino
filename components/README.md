# Components Package

## 概述

components 包定义了 Eino 框架中所有组件的抽象接口，每个组件类型都有明确的输入输出类型和选项定义。

## 子包说明

### model
定义 ChatModel 接口，用于与大语言模型交互，支持文本生成和流式输出。

### prompt
定义 ChatTemplate 接口，用于构建和格式化提示词模板。

### embedding
定义 Embedder 接口，用于将文本转换为向量表示。

### retriever
定义 Retriever 接口，用于从向量数据库或其他数据源检索相关文档。

### indexer
定义 Indexer 接口，用于将文档索引到向量数据库或其他存储系统。

### document
定义 Loader 和 Transformer 接口，用于加载和转换文档。

### tool
定义 Tool 和 ToolsNode 接口，用于工具调用和工具节点执行。

## 设计原则

- **接口透明**：组件实现对外透明，只需关注接口定义
- **类型安全**：明确的输入输出类型定义
- **可组合性**：组件可以嵌套和组合使用
- **统一选项**：每个组件类型有统一的选项定义
