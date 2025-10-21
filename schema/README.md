# Schema Package

## 概述

schema 包定义了 Eino 框架中的核心数据结构和类型，包括消息、文档、工具、流式数据等基础类型。

## 主要功能

- **消息类型**：定义 LLM 交互的消息结构（System、User、Assistant、Tool 等）
- **文档类型**：定义文档及其元数据结构
- **工具定义**：定义工具调用的接口和数据结构
- **流式处理**：提供 StreamReader 和 StreamWriter 用于流式数据处理
- **序列化支持**：支持消息和数据的序列化与反序列化

## 核心文件

- `message.go` - 消息类型定义和操作
- `document.go` - 文档类型定义
- `tool.go` - 工具定义和工具调用相关类型
- `stream.go` - 流式数据读写器实现
- `serialization.go` - 序列化和反序列化功能
- `message_parser.go` - 消息解析器

## 核心类型

- `Message` - 消息基础类型
- `Document` - 文档类型
- `ToolInfo` - 工具信息
- `ToolCall` - 工具调用
- `StreamReader[T]` - 流式数据读取器
- `StreamWriter[T]` - 流式数据写入器
