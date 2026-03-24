# gpui-demo

示例演示项目，基于 Rust + GPUI 框架 + gpui-component 组件库。

依赖版本（来自 gpui-component README）:
- gpui = "0.2.2"
- gpui-component = "0.5.1"

开发和运行

1. 安装 Rust (stable)
2. 在项目目录运行：

```bash
cargo run
```

说明

示例主程序基于 gpui-component README 的 Basic Example 写成，调用了 gpui_component::init 并在窗口中渲染一个简单的页面和按钮。根据你的平台（macOS/Linux）可能需要额外系统依赖。请参阅 GPUI 与 gpui-component 的仓库文档。

来源：
- https://github.com/zed-industries/zed/tree/main/crates/gpui
- https://github.com/longbridge/gpui-component
