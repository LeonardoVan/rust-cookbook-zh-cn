# 舌尖上的 Rust &emsp; [![Build Status travis]][travis]

[Build Status travis]: https://api.travis-ci.com/rust-lang-nursery/rust-cookbook.svg?branch=master
[travis]: https://travis-ci.com/rust-lang-nursery/rust-cookbook

《舌尖上的 Rust》是 Rust（[Rust 2018 简体中文版文档](https://books.budshome.com/rust-lang)） 程序设计语言的简要实例示例集合：展示了在 Rust 生态系统中，使用各类 crate 来完成常见编程任务的良好实践。

书中的例子都是完整的，并且经过测试，保证能正常工作，可以直接复制到你新建的 Cargo（[中文文档](https://books.budshome.com/cargo)）项目中进行使用。

> 注：《舌尖上的 Rust》翻译自 rust-lang-nursery 组织撰写的 [_"A Rust Cookbook"_](https://github.com/rust-lang-nursery/rust-cookbook)，感谢 rust-lang-nursery 组织的无私奉献！

## 在线阅读

在线阅读地址：[**《舌尖上的 Rust》** - https://books.budshome.com/rust-cookbook](https://books.budshome.com/rust-cookbook)。

## 离线阅读

如果你喜欢本地阅读方式，可以使用 mdBook（[中文文档](https://books.budshome.com/mdbook)） 进行书籍构建：

```bash
$ git clone https://github.com/zzy/rust-cookbook-zh-cn
$ cd rust-cookbook-zh-cn
$ cargo install mdbook # 指定版本使用参数：--vers "0.3.5"
$ mdbook serve --open # 或者 mdbook build
```

也可以直接用你喜欢的浏览器从 `book` 子目录打开 `index.html` 文件。

```bash
$ xdg-open ./book/index.html # linux
$ start .\book\index.html    # windows
$ open ./book/index.html     # mac
```

## 测试

如果欲运行构建本书的测试组件，请执行：

> 测试组件需要安装一些 crate，中国大陆推荐[更换默认的 Cargo 源为国内镜像源](https://books.budshome.com/cargo/reference/source-replacement.html)。

```bash
$ cargo test
```

## 贡献

《舌尖上的 Rust》的目的是让 Rust 程序员新手能够更容易地参与到 Rust 社区中，因此它需要——并欢迎你做出自己力所能及的贡献。

祝你学习愉快，欢迎提交问题，欢迎发送 PR。
