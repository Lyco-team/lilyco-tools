# lilyco-tools

Lilyco system & commercial infrastructure suite: files, grep, binfmt, plc, license & pay

本仓库为 [lilyco-42/lilyco](https://github.com/lilyco-42/lilyco) 生态的独立主题仓（Hub-and-Spoke 架构），从合并完 PR #75 / #44 / #43 后的最新 `main` 拆分而来，以便外部开发者低门槛贡献、独立编译与按主题发版。

## 包含模块

- `lilyco-files`
- `lilyco-grep`
- `lilyco-binfmt`
- `lilyco-plc`

## 快速开始

```bash
cargo check --workspace
cargo test --workspace
```
