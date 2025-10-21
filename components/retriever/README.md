# Retriever Package

## 概述

retriever 包定义了文档检索的接口。

## 主要接口

- `Retriever` - 检索器接口，根据查询检索相关文档

## 核心文件

- `interface.go` - 定义 Retriever 接口
- `option.go` - 定义检索选项（TopK、相似度阈值等）
- `callback_extra.go` - 定义检索专用的回调扩展信息

## 功能特性

- 支持向量检索
- 支持混合检索
- 可配置检索参数（TopK、过滤条件等）
- 支持回调监控
