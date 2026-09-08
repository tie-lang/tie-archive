# tie-archive

tie 项目的**历史归档**仓库：存放已经实现、已经落地或已经过时的设计规划文档，
随 tie-main 正式发行版（Harbor-2026.1-preview.5）从主仓库移出，仅作历史留档。

Archive repository for the tie project: holds design plans that have been
implemented, shipped, or superseded. These were moved out of tie-main with
the Harbor-2026.1-preview.5 release and are kept here for historical record
only.

## 内容（归档列表）/ Contents (archived plans)

| 文档 | 主题 / 状态 |
| --- | --- |
| algorithm-library.md | 算法库分类：std/ext 分层（已实现，library-v2 落地） |
| asymmetric-roadmap.md | 非对称签名/密钥交换路线（Ed25519/X25519/ECDSA P-256 已实现） |
| build-config.md | 构建配置模型 config.data.tie（已实现） |
| closure-model.md | 闭包/函数值模型（已实现） |
| compiler-decouple.md | 编译器解耦重构（已全部完成并交付） |
| dynamic-library.md | 动态库编译 DLL/.so（已实现，M5） |
| embedded-rdu.md | 嵌入式基础层 rdu（已实现，第三层内置库） |
| error-model.md | 错误处理模型 Result/Option（已实现） |
| generics.md | 泛型系统（已实现，2026-08-14 完成） |
| int-model.md | 窄整数模型 i8/i16/u8…（已实现） |
| irgen-llvm-layers.md | irgen 按 LLVM 风格分层重构（已实现） |
| library-v2.md | 三层内置库重写（已实现并随 preview.5 发布） |
| macro-model.md | 宏/元编程模型（已实现） |
| namespace-single-file.md | 单文件命名空间（已实现） |
| package-manager.md | 包管理器（已实现，tie 自写） |
| package-model.md | 库/包模型（已实现） |
| role-model.md | 文件角色扩展（已实现，S3.4 插件化） |
| self-hosting.md | 完全自举路线（已达成，tiec 自举） |
| string-model.md | 字符串模型（已实现） |
| switch-pattern-matching.md | switch 模式匹配增强（已实现） |
| table-composite.md | 复合元素表（已实现，2026-08-30） |
| tsha1-bench-report.md | TSHA1 基准报告（已发布） |
| unified-func-style.md | 统一 func 写法（已实现） |
| unsafe-model.md | unsafe 模型（已实现，凭证门禁/位姿） |

## License

本仓库使用 **Tie Public License v1.2 (TPL 1.2)**，完整文本见 [LICENSE](LICENSE)。
This repository is distributed under the **Tie Public License v1.2 (TPL 1.2)** — see [LICENSE](LICENSE) for the full text.