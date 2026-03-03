<div align="center">

<img src="fix.png" width="140" />

# Fix Scene

### Boot-time Runtime Patch for Scene

修复 Scene 无法启动守护进程的问题

<br>

**简体中文** · [English](README_EN.md) · [Русский](README_RU.md)

<br>

<img src="https://img.shields.io/badge/Android-8%2B-3DDC84?style=flat-square&logo=android&logoColor=white" />
<img src="https://img.shields.io/badge/Magisk-24%2B-00AF9C?style=flat-square" />
<img src="https://img.shields.io/badge/Root-Required-red?style=flat-square" />

<br>

</div>

---

## 项目简介

**Fix Scene** 是一个极简的、毫无技术含量的、个人使用的 Magisk 模块。

通过开机脚本运行，从`/sdcard`获取并替换 Scene 的Daemon文件，用于修复 Scene 守护进程无法启动的问题。

---

## <img src="icon.png" width="18" style="vertical-align:middle;" /> 适用项目

### 上游项目：Scene

- GitHub：https://github.com/helloklf/vtools  
- 官网：https://www.omarea.com  
- License：MIT License  

> 本项目为独立的 Magisk 修复模块，与上游作者无隶属关系。

---

## 核心代码

```sh
cp -f
