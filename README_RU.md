<div align="center">

<img src="fix.png" width="140" />

# Fix Scene

### Boot-time Runtime Patch for Scene

Исправляет проблему, когда демон Scene не запускается.

<br>

[简体中文](README.md) · [English](README_EN.md) · **Русский**

<br>

<img src="https://img.shields.io/badge/Android-8%2B-3DDC84?style=flat-square&logo=android&logoColor=white" />
<img src="https://img.shields.io/badge/Magisk-24%2B-00AF9C?style=flat-square" />
<img src="https://img.shields.io/badge/Root-Required-red?style=flat-square" />

<br>

</div>

---

## Описание

**Fix Scene** — Это минимальный, нетехнический модуль Magisk для личного использования. 

Запускается загрузочный скрипт, который извлекает и заменяет файлы Daemon для Scene из /sdcard, чтобы исправить проблему, связанную с невозможностью запуска демона Scene.


## <img src="icon.png" width="18" style="vertical-align:middle;" /> Исходный проект

### Upstream: Scene

- GitHub: https://github.com/helloklf/vtools  
- Сайт: https://www.omarea.com  
- Лицензия: MIT License  

> Это независимый модуль Magisk и не связан с автором исходного проекта.

---

## Основной фрагмент

```sh
cp -f
