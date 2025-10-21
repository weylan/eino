# Embedding Package

## 概述

embedding 包定义了文本向量化（Embedding）的接口。

## 主要接口

- `Embedder` - 向量化接口，将文本转换为向量表示

## 核心文件

- `interface.go` - 定义 Embedder 接口
- `option.go` - 定义向量化选项
- `callback_extra.go` - 定义向量化专用的回调扩展信息

## 功能特性

- 支持单文本和批量文本向量化
- 支持不同的向量化模型
- 支持回调监控
