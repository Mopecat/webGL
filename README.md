# webGL

[MDN](https://developer.mozilla.org/zh-CN/docs/Web/API/WebGL_API)

## 概念

`WebGL` 是一组基于 JavaScript 语言的图形规范，浏览器厂商按照这组规范进行实现，为 Web 开发者提供一套 3D 图形相关的 API。

这些 API 能够让 Web 开发者使用 JavaScript 语言直接和显卡（GPU）进行通信。GPU 部分对应的语言是`GLSL(openGL)`也叫着色器城区。过程是：

**CPU（WebGL 使用 JavaScript）传递数据 => 着色器程序处理数据 => 展示**

`webGL` 的基础图元有 **点，线段，三角形**
