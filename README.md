# React Native 终极优化指南（2025）

翻译自 Callstack《The Ultimate Guide To React Native Optimization 2025》

## 目录

### 介绍

- [序言](./introduction/1.Preface.md)
- [如何阅读本书](./introduction/2.How_to_Read_This_Book.md)
- [为什么性能很重要](./introduction/3.Why_Performance_Matters.md)

### 第一部份：[JavaScript](./part1/0.JavaScript.md)

- [如何分析 JavaScript 和 React 的性能](./part1/1.How_to_Profile_JS_and_React_Code.md)
- [如何测量 JavaScript 的帧率](./part1/2.How_to_Measure_JS_FPS.md)
- [如何追踪 JavaScript 的内存泄漏](./part1/3.How_to_Hunt_JS_Memory_Leaks.md)
- [非受控组件](./part1/4.Uncontrolled_Components.md)
- [高阶定制组件](./part1/5.Higher-Order_Specialized_Components.md)
- [原子化状态管理（Atomic State Management）](./part1/6.Atomic_State_Management.md)
- [并发模式下的 React（Concurrent React）](./part1/7.Concurrent_React.md)
- [React 编译器（React Compiler）](./part1/8.React_Compiler.md)
- [如何实现高性能动画且不掉帧](./part1/9.High-Performance_Animations_Without_Dropping_Frames.md)

### 第二部分：[Native](./part2/0.Native.md)

- [理解不同平台的差异](./part3/1.How_to_Analyze_JS_Bundle_Size.md)
- [如何分析 React Native 中的原生部分性能](./part2/2.How_to_Profile_Native_Parts_of_React_Native.md)
- [如何测量 TTI（Time to Interactive）](./part2/3.How_to_Measure%20TTI.md)
- [理解原生内存管理](./part2/4.Understanding_Native_Memory_Management.md)
- [理解 Turbo Modules 和 Fabric 的线程模型](./part2/5.Understand_the_Threading_Model_of_Turbo_Modules_and_Fabric.md)
- [使用 View Flattening 优化视图结构](./part2/6.Use_View_Flattening.md)
- [优先使用专用的 React Native SDK，而不是 Web 方案](./part2/7.Use_dedicated_React_Native_SDKs_Over_Web.md)
- [让你的原生模块运行得更快](./part2/8.Make_Your_Native_Modules_Faster.md)
- [如何查找原生内存泄漏](./part2/9.How_to_Hunt_Memory_Leaks.md)

### 第三部份：[Bundling](./part3/0.Bundling.md)

- [如何分析 JavaScript Bundle 的大小](./part3/1.How_to_Analyze_JS_Bundle_Size.md)
- [如何分析 App 安装包的大小](./part3/2.How_to_Analyze_App_Bundle_Size.md)
- [如何判断第三方库的实际体积](./part3/3.Determine_True_Size_of_Third-Party_Libraries.md)
- [避免使用 Barrel Exports（汇总式导出）](./part3/4.Avoid_Barrel_Exports.md)
- [尝试使用 Tree Shaking 精简代码](./part3/5.Experiment_With_Tree_Shaking.md)
- [按需远程加载代码](./part3/6.Load_Code_Remotely_When_Needed.md)
- [在 Android 中使用 R8 压缩代码](./part3/7.Shrink_Code_With_R8_Android.md)
- [使用 Native Assets 文件夹](./part3/8.Use_Native_Assets_Folder.md)
- [关闭 JavaScript Bundle 压缩](./part3/9.Disable_JS_Bundle_Compression.md)

### [关于作者](./acknowledgements/1.About_The_Authors.md)

### [本书提到的库和工具](./acknowledgements/2.Libraries_and_Tools_Mentioned_in_This_Guide.md)
