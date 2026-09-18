# GitHub 趋势分析助手

自动抓取 GitHub Trending 榜单，生成结构化技术简报的豆包自定义技能。

## ✨ 功能特性

- 自动获取当日 GitHub Trending Top10 热门项目
- 标准化输出项目名称、开发语言、核心功能、Star 数据
- 自动生成当日技术趋势简评，快速把握热点方向
- 纯提示词驱动，无需额外配置，导入即可使用

## 🚀 快速开始

1. 复制 `prompt/v1.0.0_prompt.md` 中的完整提示词
2. 打开豆包 → 技能中心 → 创建自定义技能 → 粘贴系统提示词
3. 在工作任务中发送指令即可调用

## 📌 指令示例

- 生成今日GitHub Trending Top10简报
- 今天GitHub热门项目总结
- 本周GitHub热门项目总结（支持本周/本月周期）
- 本月GitHub技术趋势分析

## 📦 版本信息

- 当前版本：v1.0.0 基础功能版
- 支持周期：仅当日榜单

## 📄 更新日志

详见 [CHANGELOG.md](./CHANGELOG.md)

## 📜 开源协议

本项目基于 [MIT License](./LICENSE) 开源，欢迎自由使用、修改与分享。

## 🗂️ 项目结构

```
github-trending-skill/
├── README.md              # 项目说明文档
├── LICENSE                # MIT 开源协议
├── CHANGELOG.md           # 版本更新日志
├── prompt/                # 技能提示词目录
│   └── v1.0.0_prompt.md   # V1.0版本完整系统提示词
├── skill-package/         # 标准技能包（可直接上传豆包）
│   └── SKILL.md           # YAML格式技能定义
└── docs/                  # 配套文档目录
    └── usage-guide.md     # 详细使用教程
```
