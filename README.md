# AI 精读书集（AI-Books）

> 把吴恩达深度学习课程笔记 + Chip Huyen《AI Engineering》等公开资料，整理成**按学习习惯排序的精读文本**，并合成**通俗易懂的中文语音（mp3）**。
> 适合通勤、排队、睡前边听边读，快速建立 AI 核心知识框架。

[![License: MIT](https://img.shields.io/badge/License-MIT-yellow.svg)](https://github.com/firemen20/ai-books/blob/main/LICENSE)
[![Audio](https://img.shields.io/badge/audio-mp3-green)](audio/)
[![Text](https://img.shields.io/badge/text-markdown-blue)](text/)

## 目录

- [学习路径](#学习路径)
- [文件结构](#文件结构)
- [怎么听 / 怎么读](#怎么听--怎么读)
- [来源与版权](#来源与版权)
- [许可](#许可)

## 学习路径

按"由浅入深"排成 10 章，分 3 段，全程约 **38 分钟**：

| 段 | 章节 | 主题 | 阶段 |
|---|---|---|---|
| 入门 | ch01 | 机器学习三兄弟（监督 / 无监督 / 强化） | 入门 |
| | ch02 | 人工智能 / 机器学习 / 深度学习 三层关系 | 入门 |
| | ch03 | 梯度下降——模型到底怎么"学会" | 入门 |
| | ch04 | 过拟合与正则化——为什么模型会"死记硬背" | 入门 |
| 进阶 | ch05 | 神经网络为什么需要"很多层" | 进阶 |
| | ch06 | CNN 为什么擅长图像 | 进阶 |
| | ch07 | RNN / LSTM 为什么需要记忆 | 进阶 |
| | ch08 | 注意力机制——Transformer 的核心 | 进阶 |
| | ch09 | GPT 到底在"猜下一个词" | 进阶 |
| 收尾 | ch10 | 模型怎么选、怎么调（面试必问） | 收尾 |

每章 200~550 字，全部用**大白话 + 生活比喻**讲"为什么"，不堆公式。

## 文件结构

```
ai-books/
├── README.md
├── LICENSE                 MIT
├── .gitignore
├── text/                   精读文本（markdown）
│   ├── fengdu78/           吴恩达深度学习课程笔记（21 章 md）
│   └── extra/              Chip Huyen《AI Engineering》+ 机器学习书单
└── audio/                  精读语音（mp3，edge-tts zh-CN-YunxiNeural）
    ├── ch01-入门/          4 个 mp3 + 4 个 txt
    ├── ch04-进阶/          5 个 mp3 + 5 个 txt
    └── ch10-收尾/         1 个 mp3 + 1 个 txt
```

> 注：`audio/ch07-高级/` 为空目录占位（音频实际都在 `ch04-进阶/`）。

## 怎么听 / 怎么读

- **听**：双击 `audio/` 下任意 `.mp3`。按 `ch01-入门` → `ch04-进阶` → `ch10-收尾` 顺序听。
- **读**：对照同目录的 `.txt`（或 `text/fengdu78/` 的原书笔记）精读。
- **生成语音用的工具**：[edge-tts](https://github.com/rany2/edge-tts)，音色 `zh-CN-YunxiNeural`（云希）。

## 来源与版权

- `text/fengdu78/` 基于 [吴恩达深度学习课程](https://github.com/fengdu78/deeplearning_ai_books)（社区整理的课程笔记）。
- `text/extra/` 收录 [Chip Huyen - AI Engineering](https://github.com/chiphuyen/aie-book) 等公开资料索引。
- `audio/` 的 txt 为本人按上述资料**重新整理**的精读文本，mp3 由 edge-tts 在线合成。

本仓库只收录**公开可得**的学习资料，若原权利人认为此处不当收录，请开 issue 或联系账号 firemen20，会及时处理。

## 许可

MIT。详见 [LICENSE](LICENSE)。
