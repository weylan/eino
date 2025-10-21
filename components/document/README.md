# Document Package

## 概述

document 包定义了文档加载和转换的接口。

## 主要接口

- `Loader` - 文档加载器接口，从各种数据源加载文档
- `Transformer` - 文档转换器接口，对文档进行转换处理

## 核心文件

- `interface.go` - 定义 Loader 和 Transformer 接口
- `option.go` - 定义加载和转换选项
- `callback_extra_loader.go` - 定义加载器专用的回调扩展信息
- `callback_extra_transformer.go` - 定义转换器专用的回调扩展信息

## 子包

### parser
提供各种文档解析器实现（PDF、Word、Markdown 等）。

## 功能特性

- 支持多种文档格式
- 支持文档分块
- 支持文档清洗
- 支持回调监控
