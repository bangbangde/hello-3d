# WebGL 概述

## 三维图形渲染技术

在 PC 上使用最广泛的两种三维图形渲染技术是 Direct3D 和 OpenGL。

Direct3D 是微软 DirectX 技术的一部分，主要用于 Windows 平台，

而 OpenGL 是开放免费的跨平台技术。

## WebGL 起源

![img.png](img.png)
<center>摘自《WebGL编程指南》</center>


## 相关概念

### 可编程着色器方法（programmable shader functions）

这是 OpenGL2.0 开始引入的一项重要特性。

一般简称着色器，编写着色器的语言类似 C 语言，又称为“着色器语言“（shading language）。

OpenGL ES2.0 基于 OpenGL 着色器语言(GLSL)，因此后者又被称为 OpenGL ES 着色器语言(GLSL ES)。

WebGL 基于OpenGLES 2.0，也使用 GLSL ES 编写着色器。

**通常 GLSL ES 是以字符串的形式在 JavaScript 中编写**。
