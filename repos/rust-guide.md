# Rust guide

> [项目地址](https://github.com/VWWL/rust-guide)

## [Programmer Dojo by Rust](https://github.com/VWWL/rust-guide/tree/master/src/dojo)

### Dojo

#### 简介

本脚手架修改自 [熊节老师](https://github.com/gigix) 的练功房脚手架，将原本的Java实现改至Rust实现，测试使用Rust自带的测试框架 + [codecov](https://codecov.io/gh/VWWL/rust-guide) 实现。

原始脚手架仓库：https://github.com/gigix/dojo-scaffold.git

## [Design patterns by Rust](https://github.com/VWWL/rust-guide/tree/master/src/design_pattern)

### 使用Rust实现设计模式

| Name | Description |
| ---  | ---         |
| [策略模式（Strategy Pattern）](./strategy_pattern/content.rs)| 将if...else...硬编码转变为dynamic trait. 编译时分支变为运行时分支。</br>关注点分离，判断逻辑放在一起，业务逻辑根据不同分支进行不同的trait实现。 |

持续更新中...


[![Basic](https://github.com/VWWL/rust-guide/actions/workflows/main.yml/badge.svg)](https://github.com/VWWL/rust-guide/actions/workflows/main.yml/badge.svg)
[![codecov](https://codecov.io/gh/VWWL/rust-guide/branch/master/graph/badge.svg)](https://codecov.io/gh/VWWL/rust-guide)

## How to deploy, run, and redevelop

Run following script to install rustup:
~~~shell
brew install rustup
~~~

Run the following script to prepare development environment:
~~~shell
cargo build
~~~

Run the following script to verify that the development environment is working, or to test and validate the use case.
~~~shell
sh ./scripts/check-all.sh
~~~

## Attention
Test coverage must be 100%.

## The role of this repository

Learn Rust grammar and practice.
