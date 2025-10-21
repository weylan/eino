# Internal Package

## 概述

internal 包包含 Eino 框架的内部实现，不对外暴露，仅供框架内部使用。

## 子包说明

### callbacks
内部回调机制实现，提供回调注入和管理功能。

### serialization
内部序列化实现，支持数据的序列化和反序列化。

### safe
提供 panic 恢复等安全机制。

### gmap
泛型 map 工具函数。

### gslice
泛型 slice 工具函数。

### generic
泛型相关的工具函数和类型操作。

### mock
测试用的 mock 组件实现。

## 注意事项

此包中的所有内容仅供 Eino 框架内部使用，不保证 API 稳定性，外部代码不应依赖此包。
