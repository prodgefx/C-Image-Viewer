# 🖼️ Image Viewer (C + SDL2)

A lightweight **SDL2-based image viewer** written in C.

## ✨ Features
- Reads **raw RGB pixel data** from `stdin`
- Parses **image dimensions** from input
- Renders pixels directly into an **SDL window surface**
- Supports interactive window closing via **SDL events**

## ⚙️ Build Instructions
Compile with `gcc` and link against SDL2:

```bash
gcc -Wall -Wextra -g -o iv iv.c `sdl2-config --cflags --libs`

```
## 🚀 Usage

Pipe an image file into the viewer:

```bash
cat <image.ext> | ./iv

```
## 📚 Notes

- Input format must provide dimensions followed by raw RGB pixel data.
- The viewer renders pixels manually, demonstrating low-level graphics rendering and manual pixel manipulation with SDL2.
