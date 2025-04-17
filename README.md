# React Native终极优化指南（2025）
翻译自Callstack《The Ultimate Guide To React Native Optimization 2025》 

## 目录

### 介绍
* [序言](https://github.com/zhongdeng/The-Ultimate-Guide-To-React-Native-Optimization-2025/blob/main/Introduction/Preface.md)
* [如何阅读本书](https://github.com/zhongdeng/The-Ultimate-Guide-To-React-Native-Optimization-2025/blob/main/Introduction/How-to-Read-This-Book.md)
* [为什么性能很重要](https://github.com/zhongdeng/The-Ultimate-Guide-To-React-Native-Optimization-2025/blob/main/Introduction/Why-Performance-Matters.md)

### 第一部份：JavaScript
* [如何分析 JavaScript 和 React 的性能]()
* [如何测量 JavaScript 的帧率（FPS）]()
* [如何查找 JavaScript 内存泄漏]()
* [非受控组件]()
* [高阶定制组件（Higher-Order Specialized Components）]()
* [原子化状态管理（Atomic State Management）]()
* [并发模式下的 React（Concurrent React）]()
* [React 编译器（React Compiler）]()
* [如何实现高性能动画且不掉帧]()

### 第二部分：原生（Native）
* [理解不同平台的差异]()
* [如何分析 React Native 中的原生部分性能]()
* [如何测量 TTI（Time to Interactive）]()
* [理解原生内存管理]()
* [理解 Turbo Modules 和 Fabric 的线程模型]()
* [使用 View Flattening 优化视图结构]()
* [优先使用专用的 React Native SDK，而不是 Web 方案]()
* [让你的原生模块运行得更快]()
* [如何查找原生内存泄漏]()

### 第三部份：打包（Bundling）
* [如何分析 JavaScript Bundle 的大小]()
* [如何分析 App 安装包的大小]()
* [如何判断第三方库的实际体积]()
* [避免使用 Barrel Exports（汇总式导出）]()
* [尝试使用 Tree Shaking 精简代码]()
* [按需远程加载代码]()
* [在 Android 中使用 R8 压缩代码]()
* [使用 Native Assets 文件夹]()
* [关闭 JavaScript Bundle 压缩]()

### [致谢]()
### [关于作者]()
### [本书提到的库和工具]()
