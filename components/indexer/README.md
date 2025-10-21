# Indexer Package

## 概述

indexer 包定义了文档索引的接口。

## 主要接口

- `Indexer` - 索引器接口，将文档索引到存储系统

## 核心文件

- `interface.go` - 定义 Indexer 接口
- `option.go` - 定义索引选项
- `callback_extra.go` - 定义索引专用的回调扩展信息

## 功能特性

- 支持批量索引
- 支持向量索引
- 支持元数据索引
- 支持回调监控
