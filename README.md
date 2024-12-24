# GUETzhihuiEng - 桂电智慧英语平台自主爬题答题助手

## 项目介绍

GUETzhihuiEng 是一个为桂林电子科技大学智慧英语平台开发的自主爬题答题助手。该项目基于前辈的代码进行了改进和优化，旨在提升用户体验和答题效率。项目通过爬取题库数据并进行自动答题，帮助学生更加高效地完成学习任务。

**主要功能**：
- 自动爬取智慧英语平台的题库内容。
- 自动选择并提交答题。
- 自定义设置登录账号（需要提供有效账号进行爬取）。

**注意**：
- 爬取功能需要提供做完题的登录账号信息，以便访问平台并进行题库爬取。

## 项目改进

该项目在前辈的基础上进行了一些修复和优化，具体包括：
- **修复了第一页链接获取不到的问题**：解决了原代码中由于页面加载问题导致无法获取第一页链接的 bug。
- **使用显式等待代替睡眠函数**：通过显式等待来确保页面元素加载完成后再进行操作，避免了因为网络卡顿导致页面元素没加载获取不到。
- **优化页面链接**：改进了页面链接获取方式，可以适应所有页面情况。


### 安装依赖
```bash
pip install -r requirements.txt

### 使用说明
- 看注释

