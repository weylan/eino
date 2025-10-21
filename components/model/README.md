# Model Package

## 概述

model 包定义了与大语言模型（LLM）交互的接口和类型。

## 主要接口

- `ChatModel` - 聊天模型接口，支持生成文本和流式输出

## 核心文件

- `interface.go` - 定义 ChatModel 接口
- `option.go` - 定义模型调用选项（温度、top_p 等）
- `callback_extra.go` - 定义模型专用的回调扩展信息

## 功能特性

- 支持同步和流式生成
- 支持工具调用（Function Calling）
- 可配置生成参数（温度、最大 token 数等）
- 支持回调监控
