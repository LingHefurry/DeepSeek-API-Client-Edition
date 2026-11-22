# DeepSeek-API-Client-Edition
DeepSeek API Client Edition for Legacy Systems
# D.S.C.E

> D.S.C.E.面向经典 Windows 系统的 DeepSeek API 桌面客户端。

 D.S.C.E.是一款面向经典 Windows 桌面环境开发的 DeepSeek API 客户端。目前主要以 NT5.x NT6.x 9x（32 位 64位）作为开发和适配目标。

---

## 项目概况

| 项目 | 信息 |

|:---|:---|

| 软件名称 | DeepSeek-API-Client-Edition |

| 软件类型 | DeepSeek API 客户端 |

| 当前版本 | **0.10.0 RC1** |

| 内部版本编号 | `build xxxxxx-zzyy ` |

| 发布阶段 | Release Candidate 1 |

| 目标系统 | Windows XP SP3 / Windows Vista / Windows 7 |

| 系统架构 | x86 x64（32-bit） |

| 运行框架 | .NET Framework 4.0 |

| 发布形式 | Windows Installer |

| 源代码 | 仅公开RC1源文件 |

## 系统要求

### 基本运行环境

| 项目 | 要求 |

|:---|:---|

| 操作系统 | Windows XP SP3 Windows Vista Windows 7  |

| 系统架构 | 32 位 64 位（x86 windows XP x64暂未支持） |

| 运行框架 | Microsoft .NET Framework 4.0 |

| 网络 | 可用的 Internet 连接 |

| API | 有效的 DeepSeek API Key |

### 相关组件与依赖

| 组件 | 用途 | 说明 |

|:---|:---|:---|

| .NET Framework 4.0 | 程序运行环境 | 必需 |

| libcurl x86 | HTTP/HTTPS 网络通信 | **内置，无需单独安装** |

| OpenSSL | HTTPS 加密通信 | 以安装包实际内容为准 |

| Microsoft Speech API / SAPI | 语音功能 | 根据系统环境检测 |

| Speech SDK 5.1 | 语音识别支持 | 根据实际需求检测 |

| Speech SDK 5.1 Language Pack | 简体中文语音识别 | 根据实际需求检测 |

> 注意：libcurl x86 以及网络补丁已集成于 Vesper，用户无需单独下载或安装。其他组件是否需要额外安装，以安装程序的实际检测结果为准。

## 功能介绍

| 功能 | 说明 |

|:---|:---|

| API Connection | DeepSeek API 网络连接 |

| Desktop Chat | 桌面聊天界面 |

| Voice Input | 语音输入 |

| Chat History | 本地聊天记录保存与管理 |

| History Import | 导入 DeepSeek 导出的聊天记录 |

| Chat Export (Backup) | 导出本地聊天 |

| Image Attachment | 图片附件及视觉输入 |

| API Key Settings | API Key 配置与保存 |

| Application Settings | 应用程序设置 |

| System Diagnostics | 系统信息与诊断 |

| AI Agent (Harness) | AI 代理与权限管控



*具体功能以实际发布的 RC 版本为准。*

---

## 下载与安装

当前版本通过 GitHub Releases 发布。

**当前公开版本：** `D.S.C.E 0.10.0 RC 1Code Name：“Dawn”`

1. 进入本项目的 GitHub Releases 页面。

2. 找到 `D.S.C.E 0.10.0 RC`。

3. 下载 `Setup.exe`。

4. 运行安装程序。

5. 按照安装向导完成系统检测及安装。

6. 启动 D.S.C.E，并配置 DeepSeek API Key。

请优先从本项目的 GitHub Releases 页面获取安装程序。

## 历史版本

### D.S.C.E 0.5.0 Preview （**过时的版本*）

<sup>First Public Preview — 首个公开预览版</sup>

**Build:** `000500-0401`

这是 D.S.C.E 的第一个公开预览版本，主要用于公开测试、收集反馈以及检查程序在目标系统上的运行情况。

本次发布包含：

- DeepSeek API 网络连接

- 桌面聊天界面

- 语音输入

- 本地聊天记录管理

- 聊天记录导入

- 图片附件及视觉输入

- API Key 配置与保存

- 应用程序设置

- 系统信息与诊断

**发布阶段：** Preview

## 兼容性说明

目前 Vesper 主要针对 Windows XP SP3 x86 进行开发和适配。

| 操作系统 | 当前状态 |

|:---|:---|

| Windows XP SP3 / Windows Vista| 主要目标平台 |

| Windows NT 5.0 系列 | 后续适配计划 |

| Windows 98 SE | 后续适配计划 |

其他经典 Windows 系统仍需进一步适配和测试，不代表当前版本已经获得完整支持。

## 问题反馈

如果在安装或使用过程中遇到问题，可以通过 GitHub Issues 提交反馈。

建议提供：

- Windows 版本及 Service Pack

- 系统架构

- 错误提示或截图

- 问题出现时的操作步骤

请勿在问题报告中公开 API Key、密码或私人聊天记录。

## 项目源代码

目前项目源代码仅公开RC1。

当前 GitHub 仓库主要用于发布项目介绍、版本记录及安装程序。

## 声明

Vesper 是独立开发的第三方 DeepSeek API 客户端，并非 DeepSeek 官方产品。

DeepSeek 名称及相关商标归其各自所有者所有。

---

<p align="center">

**Vesper — DeepSeek API Client Edition**

*For the classic Windows desktop.*



</p>
