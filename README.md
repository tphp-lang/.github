# tphp-lang

> PHP → C AOT 编译器 · 写 PHP，编译成原生二进制。零运行时，极致性能。

```php
// hello.php（<?php 可选）
class Main {
    public function main(): void {
        echo "你好，世界！\n";
    }
}
```

```bash
$ tphp hello.php && ./hello
你好，世界！
```

---

## 为什么选 tphp？

- 🚀 **原生性能**：数组操作比传统 PHP 快 18-36 倍，方法调用优化至 0ns
- 📦 **单文件部署**：编译成一个独立二进制，无需 PHP 运行时
- 🔧 **230+ 内置函数**：覆盖字符串、数组、JSON、哈希、文件、日期等常用 API
- 🖥️ **全平台**：Linux / macOS / Windows x86_64 + ARM

## 仓库

| 仓库 | 说明 |
|------|------|
| **[tphp](https://github.com/tphp-lang/TinyPHP)** | 核心编译器 |

## 链接

[📖 文档](https://github.com/tphp-lang/TinyPHP#readme) · [🚀 快速上手](https://github.com/tphp-lang/TinyPHP/blob/main/QUICK_START.md) · [📊 性能](https://github.com/tphp-lang/TinyPHP/blob/main/BENCHMARK_RESULTS.md) · [🤝 贡献](https://github.com/tphp-lang/TinyPHP/blob/main/CONTRIBUTING.md)

---

<sub>MIT License</sub>
