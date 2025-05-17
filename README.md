# Hecto 编辑器

Hecto 是一个使用 Rust 语言开发的简单而高效的终端文本编辑器。这个项目旨在创建一个轻量级的编辑器，同时也作为学习 Rust 语言的实践项目。

## 功能特性

- 终端界面文本编辑
- 基本的文本编辑功能

## 环境要求

- Rust 工具链（推荐使用 1.86.0 或更高版本）
- Cargo 包管理器

## 安装方法

1. 克隆代码仓库：

   ```bash
   git clone https://github.com/[username]/hecto.git
   cd hecto
   ```

2. 使用 Cargo 构建项目：

   ```bash
   cargo build --release
   ```

编译后的可执行文件将位于 `target/release` 目录下。

## 使用方法

运行编辑器：

```bash
cargo run hecto
```

## 开发说明

这个项目使用 Rust 的标准构建工具 Cargo 进行管理。您可以使用以下命令：

- `cargo build` - 构建项目
- `cargo run` - 运行项目
- `cargo test` - 运行测试
- `cargo check` - 检查代码但不生成可执行文件

## 项目结构

```rust
src/
  └── main.rs      # 主程序入口
```

## 贡献指南

欢迎提交 Pull Request 或创建 Issue 来帮助改进这个项目。

## 许可证

本项目采用 MIT 许可证 - 详情请参见 [LICENSE](LICENSE) 文件。
