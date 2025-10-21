# ADK (Agent Development Kit) Package

## 概述

adk 包提供了构建 AI Agent 的开发工具包，包含 Agent 的核心抽象、预置 Agent 实现和相关工具。

## 主要功能

- **Agent 接口定义**：定义 Agent 的标准接口和行为
- **ReAct Agent**：实现经典的 ReAct（Reasoning and Acting）模式
- **工具集成**：支持 Agent 调用外部工具
- **流程控制**：支持中断、恢复等流程控制能力
- **上下文管理**：提供运行时上下文管理
- **预置 Agent**：提供开箱即用的 Agent 实现

## 核心文件

- `interface.go` - Agent 接口定义
- `react.go` - ReAct Agent 实现
- `agent_tool.go` - Agent 工具集成
- `runner.go` - Agent 运行器
- `runctx.go` - 运行时上下文管理
- `flow.go` - Agent 流程编排
- `workflow.go` - Agent 工作流实现
- `interrupt.go` - 中断处理机制

## 预置 Agent

### prebuilt/planexecute
计划-执行模式的 Agent 实现。

### prebuilt/supervisor
监督者模式的多 Agent 协作实现。
