---
layout: archive
title: "AgentDeck"
permalink: /activities/agentdeck/
author_profile: true
---

{% include language-toggle.html %}

<div class="lang-en" markdown="1">

A lightweight open-source desktop prompt manager built for Windows.

## Motivation

When I work with AI tools such as Codex or ChatGPT, I keep reaching for the same few long
prompts. Scattering them across notes, chat history and old messages makes them annoying to
find and easy to lose.

AgentDeck is a small utility that stays in the background and keeps those prompts in one
place: press a global hotkey, type a few characters, press Enter, and the full prompt is on
the clipboard — ready to paste back into whatever tool I am using.

It is a prompt management and quick-recall tool, not an AI agent.

## Features

* **Global hotkey** — `Alt+Space` brings up the launcher from any application
* **Instant search** — filters across prompt name, category and content as you type
* **Plain Markdown storage** — every prompt is a normal `.md` file under `prompts/<category>/`, editable in any text editor
* **Variable placeholders** — a `{% raw %}{{VARIABLE}}{% endraw %}` in the prompt body opens a small form before copying
* **In-app management** — create, edit, rename, delete and re-categorize prompts without leaving the tool
* **Local-first** — no account, no network access, no database; lives in the system tray

## Tech

Python · PySide6 / Qt · Win32 `RegisterHotKey` (ctypes) · PyInstaller · pytest

## Open Source

AgentDeck is released under the MIT License.

[View on GitHub](https://github.com/lihaolun201003/AgentDeck)

</div>

<div class="lang-zh" style="display:none;" markdown="1">

一个面向 Windows 的轻量级开源桌面 Prompt 管理工具。

## 项目动机

在使用 Codex、ChatGPT 这类 AI 工具时，我经常要反复使用同样几段较长的 Prompt。
把它们分散记在笔记、聊天记录和历史消息里，用的时候不好找，也容易丢。

AgentDeck 是一个常驻后台的小工具，把这些 Prompt 集中放在一处：按一次全局快捷键，
输入几个字，回车，完整内容就进了剪贴板，可以直接粘贴回正在使用的 AI 工具。

它本质上是一个 Prompt 管理与快速调用工具，而不是 AI Agent。

## 核心功能

* **全局快捷键** —— 在任何程序里按 `Alt+Space` 都能呼出
* **实时搜索** —— 输入即过滤，覆盖 Prompt 名称、分类与正文
* **普通 Markdown 存储** —— 每个 Prompt 就是 `prompts/<分类>/` 下的一个 `.md` 文件，可用任意文本编辑器修改
* **变量占位符** —— 正文里的 `{% raw %}{{变量}}{% endraw %}` 会在复制前弹出填写框
* **界面内管理** —— 新建、编辑、重命名、删除、调整分类都不需要离开工具
* **纯本地运行** —— 不需要账号、不联网、不依赖数据库，常驻系统托盘

## 技术栈

Python · PySide6 / Qt · Win32 `RegisterHotKey`（ctypes）· PyInstaller · pytest

## 开源

AgentDeck 以 MIT License 开源。

[在 GitHub 上查看项目](https://github.com/lihaolun201003/AgentDeck)

</div>

<img src="/images/agentdeck-main.png"
     alt="AgentDeck main window"
     style="width:100%; max-width:850px; border-radius:8px;">

[← Back to Activities](/activities/)
