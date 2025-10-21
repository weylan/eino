# Prompt Package

## 概述

prompt 包定义了提示词模板的接口和实现。

## 主要接口

- `ChatTemplate` - 聊天模板接口，用于格式化提示词

## 核心文件

- `interface.go` - 定义 ChatTemplate 接口
- `chat_template.go` - 提供基础的聊天模板实现
- `option.go` - 定义模板选项
- `callback_extra.go` - 定义模板专用的回调扩展信息

## 功能特性

- 支持变量替换
- 支持模板组合
- 支持消息格式化
- 支持回调监控
