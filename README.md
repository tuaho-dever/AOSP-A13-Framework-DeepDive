# AOSP-Android13-Analysis & Novel-NLP-Toolkit

## 🚀 Overview
This repository contains my research notes on **Android 13 (Tiramisu)** system frameworks and a set of **NLP tools** for large-scale web novel processing.

## 🛠 Research Areas
- **Android Framework**: Deep dive into `AMS` (ActivityManagerService), `WMS` (WindowManagerService), and input dispatching systems.
- **Stability & Performance**: Root cause analysis of **ANR** and **Jank/Lag** in AOSP.
- **Novel Engineering**: Processing 3M+ words fiction for character profile extraction and AI image generation.

## 📂 Project Structure
- `/framework-notes`: Analysis on `ViewRootImpl`, `ActivityThread`, and `traces.txt`.
- `/scripts`: Python tools for chapter splitting and persona generation.

---

## 📝 笔记摘要 (Study Notes Summary)
*目前主要侧重于分析 Android 13 中 InputDispatcher 的超时机制，以及如何通过 traces 准确定位 WMS 锁竞争导致的 ANR 问题。*

## 📖 小说工具说明
*开发了一套脚本用于切割 300 万字的小说，重点在于提取“女王”等核心角色的外貌特征，并将其转化为适合 Flux 生成的高质量 Prompt。*
